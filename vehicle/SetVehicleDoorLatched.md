---
ns: VEHICLE
aliases: ["0xa5a9653a8d2caf48"]
---
## SET_VEHICLE_DOOR_LATCHED

```c
// 0xA5A9653A8D2CAF48
void SET_VEHICLE_DOOR_LATCHED(Vehicle vehicle, int DoorNumber, bool SetLatched, bool WillAutoLatch, bool ApplyForceForDoorClosed);
```

```
Sets a vehicle door to latch.

Possible values for DoorNumber:
| Index | Name |
| --- | --- |
| -1 | Invalid |
| 0 | Front Left |
| 60 | Front Right |
| 61 | Rear Left |
| 62 | Rear Right |
| 63 | Bonnet |
| 64 | Boot |


SC_DOOR_LIST is in commands_vehicle.sch
```
