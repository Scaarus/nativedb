---
ns: VEHICLE
aliases: ["0xd4d4f6a4ab575a33"]
---
## SET_VEHICLE_DOOR_BROKEN

```c
// 0xD4D4F6A4AB575A33
void SET_VEHICLE_DOOR_BROKEN(Vehicle vehicle, int DoorNumber, bool Dissapear);
```

Breaks a vehicle door.

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

