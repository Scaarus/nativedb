---
ns: VEHICLE
aliases: ["0x679be1daf71da874"]
---
## IS_VEHICLE_STUCK_TIMER_UP

```c
// 0x679BE1DAF71DA874
bool IS_VEHICLE_STUCK_TIMER_UP(Vehicle vehicle, int StuckType, int RequiredTime);
```

```
Has a timer for a specific stuck check expired.

Possible values for StuckType:
| Index | Name |
| --- | --- |
| 0 | On Roof |
| 330 | On Side |
| 331 | Hung Up |
| 332 | Jammed |
| 333 | Reset All |
```
