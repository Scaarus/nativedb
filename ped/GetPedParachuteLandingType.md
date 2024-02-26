---
ns: PED
aliases: ["0x8b9f1fc6ae8166c0"]
---
## GET_PED_PARACHUTE_LANDING_TYPE

```c
// 0x8B9F1FC6AE8166C0
int GET_PED_PARACHUTE_LANDING_TYPE(Ped ped);
```

Gets the current landing type of the Parachuting Ped (returns PPLT_INVALID if the Ped isn't landing).

## Return Type Values:
| Value | Name |
| --- | --- |
| -1 | Invalid |
| 0 | Slow |
| 1 | Regular |
| 2 | Fast |
| 3 | Crash |
| 4 | Water |

