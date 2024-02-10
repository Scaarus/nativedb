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
| 60 | Front Right |
| 61 | Rear Left |
| 62 | Rear Right |
| 63 | Bonnet |
| 64 | Boot |


SC_DOOR_LIST is in commands_vehicle.sch

