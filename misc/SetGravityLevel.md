---
ns: MISC
aliases: ["0x740e14fad5842351"]
---
## SET_GRAVITY_LEVEL

```c
// 0x740E14FAD5842351
void SET_GRAVITY_LEVEL(int iGravityLevel);
```

Changes the current gravity level

## Values for `iGravityLevel`:
| Value | Name |
| --- | --- |
| 0 | Earth |
| 1 | Moon |
| 2 | Low |
| 3 | Zero |


Should be done at the start of a level or after a cutscene. Not advisable to change during normal play.

