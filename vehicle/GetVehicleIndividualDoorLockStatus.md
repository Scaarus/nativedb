---
ns: VEHICLE
aliases: ["0xca4ac3eaae46ec7b"]
---
## GET_VEHICLE_INDIVIDUAL_DOOR_LOCK_STATUS

```c
// 0xCA4AC3EAAE46EC7B
int GET_VEHICLE_INDIVIDUAL_DOOR_LOCK_STATUS(Vehicle vehicle, int DoorIndex);
```

Gets the door lock status for given door index.

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

