---
ns: VEHICLE
aliases: ["0x679be1daf71da874"]
---
## IS_VEHICLE_STUCK_TIMER_UP

```c
// 0x679BE1DAF71DA874
bool IS_VEHICLE_STUCK_TIMER_UP(Vehicle vehicle, int StuckType, int RequiredTime);
```

Has a timer for a specific stuck check expired.

## StuckType Values:
| Value | Name |
| --- | --- |
| 0 | On Roof |
| 1 | On Side |
| 2 | Hung Up |
| 3 | Jammed |
| 4 | Reset All |

