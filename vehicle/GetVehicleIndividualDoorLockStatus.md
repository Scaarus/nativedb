---
ns: VEHICLE
aliases: ["0xca4ac3eaae46ec7b"]
---
## GET_VEHICLE_INDIVIDUAL_DOOR_LOCK_STATUS

```c
// 0xCA4AC3EAAE46EC7B
lock_state GET_VEHICLE_INDIVIDUAL_DOOR_LOCK_STATUS(Vehicle vehicle, int DoorIndex);
```

```
Gets the door lock status for given door index.

Possible return values:
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
```
