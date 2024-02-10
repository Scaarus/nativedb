---
ns: VEHICLE
aliases: ["0x5845066d8a1ea7f7"]
---
## SET_ADDITIONAL_ROTATION_FOR_RECORDED_VEHICLE_PLAYBACK

```c
// 0x5845066D8A1EA7F7
void SET_ADDITIONAL_ROTATION_FOR_RECORDED_VEHICLE_PLAYBACK(Vehicle vehicle, Vector3 Rotation, int RotOrder);
```

```
Applies an additional rotation to a plane upon which a vehicle recording is currently playing back.

Possible values for RotOrder:
| Index | Name |
| --- | --- |
| 0 | Xyz |
| 1 | Xzy |
| 2 | Yxz |
| 3 | Yzx |
| 4 | Zxy |
| 5 | Zyx |
| 6 | Max |
```

## Parameters
* **vehicle**: 
* **Rotation**: The amount of addition rotation to apply, expressed as Euler angles in degrees.
* **RotOrder**: Defines the rotation order to use when composing a rotation matrix from Euler angles, defaults to YXZ order, which will be appropriate for almost all uses.
