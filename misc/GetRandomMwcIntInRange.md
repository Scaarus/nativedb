---
ns: MISC
aliases: ["0xf2d49816a804d134"]
---
## GET_RANDOM_MWC_INT_IN_RANGE

```c
// 0xF2D49816A804D134
int GET_RANDOM_MWC_INT_IN_RANGE(int MinInt, int MaxInt);
```

```
Gets a random int from the MWC RNG with range passed in. Be careful - this will only ever return integers between MinInt and (MaxInt-1) inclusive. e.g. GET_RANDOM_INT_IN_RANGE(0, 5) will only ever return 0, 1, 2, 3 or 4. It will never return 5.

Default vaules min int = 0 and max int = 65535
```
