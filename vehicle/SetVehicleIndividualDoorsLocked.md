---
ns: VEHICLE
aliases: ["0xbe70724027f85bcd"]
---
## SET_VEHICLE_INDIVIDUAL_DOORS_LOCKED

```c
// 0xBE70724027F85BCD
void SET_VEHICLE_INDIVIDUAL_DOORS_LOCKED(Vehicle vehicle, int DoorIndex, int NewLockState);
```

```
Set the given doors to a certain locked state.

Possible values for NewLockState:
| Index | Name |
| --- | --- |
| 0 | None |
| 24 | Unlocked 1 |
| 25 | Locked 2 |
| 26 | Lockout Player Only 3 |
| 27 | Locked Player Inside 4 |
| 28 | Locked Initially 5 |
| 29 | Force Shut Doors 6 |
| 30 | Locked But Can Be Damaged 7 |
| 31 | Locked But Boot Unlocked 8 |
| 32 | Locked No Passengers 9 |
| 33 | Cannot Enter 10 |


LOCK_STATE is in commands_vehicle.sch
```
