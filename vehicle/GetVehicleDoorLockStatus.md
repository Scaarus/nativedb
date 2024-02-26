---
ns: VEHICLE
aliases: ["0x25bc98a59c2ea962"]
---
## GET_VEHICLE_DOOR_LOCK_STATUS

```c
// 0x25BC98A59C2EA962
int GET_VEHICLE_DOOR_LOCK_STATUS(Vehicle vehicle);
```

Gets the vehicle lock status.

## Return Type Values:
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

