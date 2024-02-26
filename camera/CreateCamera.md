---
ns: CAMERA
aliases: ["0x5e3cf89c6bcca67d"]
---
## CREATE_CAMERA

```c
// 0x5E3CF89C6BCCA67D
Camera CREATE_CAMERA(int Camera, bool StartActivated);
```

Create a camera of a given name.

## Camera Values:
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


StartActivated sets if the camera starts acive

