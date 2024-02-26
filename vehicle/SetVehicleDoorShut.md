---
ns: VEHICLE
aliases: ["0x93d9bd300d7789e5"]
---
## SET_VEHICLE_DOOR_SHUT

```c
// 0x93D9BD300D7789E5
void SET_VEHICLE_DOOR_SHUT(Vehicle vehicle, int DoorNumber, bool ShutInstantly);
```

Shuts a vehicle door.

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

