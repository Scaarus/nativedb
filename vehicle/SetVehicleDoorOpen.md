---
ns: VEHICLE
aliases: ["0x7c65dac73c35c862"]
---
## SET_VEHICLE_DOOR_OPEN

```c
// 0x7C65DAC73C35C862
void SET_VEHICLE_DOOR_OPEN(Vehicle vehicle, int DoorNumber, bool SwingFree, bool Instant);
```

Opens a vehicle door.

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

