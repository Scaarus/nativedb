---
ns: VEHICLE
aliases: ["0x3b458ddb57038f08"]
---
## SET_VEHICLE_DOOR_AUTO_LOCK

```c
// 0x3B458DDB57038F08
void SET_VEHICLE_DOOR_AUTO_LOCK(Vehicle vehicle, int DoorNumber, bool AutoLock);
```

Sets a vehicle door to auto lock when closed.

## DoorNumber Values:
| Value | Name |
| --- | --- |
| -1 | Invalid |
| 0 | Front Left |
| 1 | Front Right |
| 2 | Rear Left |
| 3 | Rear Right |
| 4 | Bonnet |
| 5 | Boot |


SC_DOOR_LIST is in commands_vehicle.sch

