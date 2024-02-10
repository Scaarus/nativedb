---
ns: TASK
aliases: ["0x8c825bdc7741d37c"]
---
## SET_HIGH_FALL_TASK

```c
// 0x8C825BDC7741D37C
void SET_HIGH_FALL_TASK(Ped ped, int nMinTime, int nMaxTime, int type);
```

```
Give the ped an NM HighFall task. This is good for falling anf rolling after hitting the ground if it's a slope

Possible values for type:
| Index | Name |
| --- | --- |
| 0 | In Air |
| 1 | Vault |
| 2 | From Car Hit |
| 3 | Slope Slide |
| 4 | Teeter Edge |
| 5 | Sprint Exhausted |
| 6 | Stunt Jump |
```

## Parameters
* **ped**: 
* **nMinTime**: 
* **nMaxTime**: minimum and maximum time to run the task for.
* **type**: 
