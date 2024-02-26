---
ns: VEHICLE
aliases: ["0xa5a9653a8d2caf48"]
---
## SET_VEHICLE_DOOR_LATCHED

```c
// 0xA5A9653A8D2CAF48
void SET_VEHICLE_DOOR_LATCHED(Vehicle vehicle, int DoorNumber, bool SetLatched, bool WillAutoLatch, bool ApplyForceForDoorClosed);
```

Sets a vehicle door to latch.

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

