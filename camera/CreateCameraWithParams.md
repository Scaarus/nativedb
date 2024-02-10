---
ns: CAMERA
aliases: ["0x6abfa3e16460f22d"]
---
## CREATE_CAMERA_WITH_PARAMS

```c
// 0x6ABFA3E16460F22D
Camera CREATE_CAMERA_WITH_PARAMS(int Camera, Vector3 vecPos, Vector3 vecRot, bool StartActivated, int RotOrder);
```

Create a camera of a given name.

## Camera Values:
| Value | Name |
| --- | --- |
| 65 | Scripted |
| 66 | Scripted Fly An In-Game Fly Camera Designed For Use In The Mission Creator |
| 67 | Animated |
| 68 | Transition |
| 69 | Spline Default Smoothed And Velocity Constrained Spline, Not Continous Velocity |
| 70 | Spline Timed Smoothed And Velocity Constrained Spline, Not Continous Velocity |
| 71 | Spline Rounded Rounded Spline With Continous Velocity |
| 72 | Spline Smoothed Smoothed Spline With Continous Velocity |
| 73 | Spline Timed Custom Smoothed And Velocity Constrained Spline, Not Continous Velocity, Custom Speeds Can Be Set |


## RotOrder Values:
| Value | Name |
| --- | --- |
| 0 | Xyz |
| 1 | Xzy |
| 2 | Yxz |
| 3 | Yzx |
| 4 | Zxy |
| 5 | Zyx |
| 6 | Max |


StartActivated sets if the camera starts acive

