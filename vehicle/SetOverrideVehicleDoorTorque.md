---
ns: VEHICLE
aliases: ["0x66e3aaface2d1eb8"]
---
## SET_OVERRIDE_VEHICLE_DOOR_TORQUE

```c
// 0x66E3AAFACE2D1EB8
void SET_OVERRIDE_VEHICLE_DOOR_TORQUE(int DoorNumber, bool OverrideTorque);
```

Sets whether the door should use increased torque to drive it to position. If this is set the door will open faster and be harder to move.

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

