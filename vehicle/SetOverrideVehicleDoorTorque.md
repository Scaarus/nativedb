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
| 60 | Front Right |
| 61 | Rear Left |
| 62 | Rear Right |
| 63 | Bonnet |
| 64 | Boot |

