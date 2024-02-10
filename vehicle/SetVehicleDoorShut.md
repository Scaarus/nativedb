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
| 60 | Front Right |
| 61 | Rear Left |
| 62 | Rear Right |
| 63 | Bonnet |
| 64 | Boot |


SC_DOOR_LIST is in commands_vehicle.sch

