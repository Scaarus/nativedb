---
ns: VEHICLE
aliases: ["0xd7591b0065afaa7a"]
---
## RESET_VEHICLE_STUCK_TIMER

```c
// 0xD7591B0065AFAA7A
void RESET_VEHICLE_STUCK_TIMER(Vehicle vehicle, int StuckType);
```

Resets a vehicles stuck check.

## StuckType Values:
| Value | Name |
| --- | --- |
| 0 | On Roof |
| 1 | On Side |
| 2 | Hung Up |
| 3 | Jammed |
| 4 | Reset All |


eVehStuckTypes is in ciommands_vehicle.sch

