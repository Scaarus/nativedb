---
ns: VEHICLE
aliases: ["0xfe3f9c29f7b32bd5"]
---
## GET_VEHICLE_DOOR_ANGLE_RATIO

```c
// 0xFE3F9C29F7B32BD5
float GET_VEHICLE_DOOR_ANGLE_RATIO(Vehicle vehicle, int DoorNumber);
```

Gets the door angle of a door between 0.0 and 1.0.

## Values for `DoorNumber`:
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

