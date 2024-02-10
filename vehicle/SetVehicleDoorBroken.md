---
ns: VEHICLE
aliases: ["0xd4d4f6a4ab575a33"]
---
## SET_VEHICLE_DOOR_BROKEN

```c
// 0xD4D4F6A4AB575A33
void SET_VEHICLE_DOOR_BROKEN(Vehicle vehicle, int DoorNumber, bool Dissapear);
```

```
Breaks a vehicle door.

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
