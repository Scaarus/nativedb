---
ns: VEHICLE
aliases: ["0xb8e181e559464527"]
---
## IS_VEHICLE_DOOR_DAMAGED

```c
// 0xB8E181E559464527
bool IS_VEHICLE_DOOR_DAMAGED(Vehicle vehicle, int DoorNumber);
```

Checks if the vehicle door is intact

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

