---
ns: PED
aliases: ["0x6a03bf943d767c93"]
---
## IS_PED_IN_HIGH_COVER

```c
// 0x6A03BF943D767C93
bool IS_PED_IN_HIGH_COVER(Ped ped);
```

Checks if the ped is currently in high cover, will return false if in low cover. This will also return false and assert if the ped is not in cover at all, so you should call [`IS_PED_IN_COVER`](#_0x60DFD0691A170B88) first.

