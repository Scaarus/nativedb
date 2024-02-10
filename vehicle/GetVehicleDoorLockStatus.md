---
ns: VEHICLE
aliases: ["0x25bc98a59c2ea962"]
---
## GET_VEHICLE_DOOR_LOCK_STATUS

```c
// 0x25BC98A59C2EA962
lock_state GET_VEHICLE_DOOR_LOCK_STATUS(Vehicle vehicle);
```

```
Gets the vehicle lock status.

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
