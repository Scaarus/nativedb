---
ns: CAMERA
aliases: ["0x5e3cf89c6bcca67d"]
---
## CREATE_CAMERA

```c
// 0x5E3CF89C6BCCA67D
Camera CREATE_CAMERA(int Camera, bool StartActivated);
```

```
Create a camera of a given name.

Possible values for Camera:
| Index | Name |
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


StartActivated sets if the camera starts acive
```
