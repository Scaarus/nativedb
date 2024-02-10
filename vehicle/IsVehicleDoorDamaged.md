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

