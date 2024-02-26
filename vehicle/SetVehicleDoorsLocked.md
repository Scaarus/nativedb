---
ns: VEHICLE
aliases: ["0xb664292eaecf7fa6"]
---
## SET_VEHICLE_DOORS_LOCKED

```c
// 0xB664292EAECF7FA6
void SET_VEHICLE_DOORS_LOCKED(Vehicle vehicle, int NewLockState);
```

Set the vehicle doors to a certain locked state.

## NewLockState Values:
| Value | Name |
| --- | --- |
| 0 | None |
| 1 | Unlocked (1) |
| 2 | Locked (2) |
| 3 | Lockout Player Only (3) |
| 4 | Locked Player Inside (4) |
| 5 | Locked Initially (5) |
| 6 | Force Shut Doors (6) |
| 7 | Locked But Can Be Damaged (7) |
| 8 | Locked But Boot Unlocked (8) |
| 9 | Locked No Passengers (9) |
| 10 | Cannot Enter (10) |


LOCK_STATE is in commands_vehicle.sch

