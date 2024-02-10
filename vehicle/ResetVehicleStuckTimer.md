---
ns: VEHICLE
aliases: ["0xd7591b0065afaa7a"]
---
## RESET_VEHICLE_STUCK_TIMER

```c
// 0xD7591B0065AFAA7A
void RESET_VEHICLE_STUCK_TIMER(Vehicle vehicle, int StuckType);
```

```
Resets a vehicles stuck check.

Possible values for StuckType:
| Index | Name |
| --- | --- |
| 0 | On Roof |
| 330 | On Side |
| 331 | Hung Up |
| 332 | Jammed |
| 333 | Reset All |


eVehStuckTypes is in ciommands_vehicle.sch
```
