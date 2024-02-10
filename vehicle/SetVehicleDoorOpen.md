---
ns: VEHICLE
aliases: ["0x7c65dac73c35c862"]
---
## SET_VEHICLE_DOOR_OPEN

```c
// 0x7C65DAC73C35C862
void SET_VEHICLE_DOOR_OPEN(Vehicle vehicle, int DoorNumber, bool SwingFree, bool Instant);
```

```
Opens a vehicle door.

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
