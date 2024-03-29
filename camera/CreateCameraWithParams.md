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

## Values for `Camera`:
| Value | Name |
| --- | --- |
| 0 | Scripted |
| 1 | Scripted Fly (An In-Game Fly Camera Designed For Use In The Mission Creator) |
| 2 | Animated |
| 3 | Transition |
| 4 | Spline Default (Smoothed And Velocity Constrained Spline, Not Continous Velocity) |
| 5 | Spline Timed (Smoothed And Velocity Constrained Spline, Not Continous Velocity) |
| 6 | Spline Rounded (Rounded Spline With Continous Velocity) |
| 7 | Spline Smoothed (Smoothed Spline With Continous Velocity) |
| 8 | Spline Timed Custom (Smoothed And Velocity Constrained Spline, Not Continous Velocity, Custom Speeds Can Be Set) |


## Values for `RotOrder`:
| Value | Name |
| --- | --- |
| 0 | Xyz |
| 1 | Xzy |
| 2 | Yxz |
| 3 | Yzx |
| 4 | Zxy |
| 5 | Zyx |


StartActivated sets if the camera starts acive


## Parameters
* **Camera**: 
* **vecPos**: 
* **vecRot**: 
* **StartActivated**: (Default value: `False`)
* **RotOrder**: (Default value: `Yxz`)
