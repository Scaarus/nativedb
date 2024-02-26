---
ns: CAMERA
aliases: ["0x9fbda379383a52a4"]
---
## SET_CAM_ACTIVE_WITH_INTERP

```c
// 0x9FBDA379383A52A4
void SET_CAM_ACTIVE_WITH_INTERP(Camera camera, Camera camera, int Duration, int GraphTypePos, int GraphTypeRot);
```

Sets a cam active which will interpolated too.

## GraphTypePos Values:
| Value | Name |
| --- | --- |
| 0 | Linear |
| 1 | Sin Accel Decel (Accelerates At Start, Decelerates At End) |
| 2 | Accel (Just Acceleration) |
| 3 | Decel (Just Deceleration) |
| 4 | Slow In |
| 5 | Slow Out |
| 6 | Slow In Out |
| 7 | Very Slow In |
| 8 | Very Slow Out |
| 9 | Very Slow In Slow Out |
| 10 | Slow In Very Slow Out |
| 11 | Very Slow In Very Slow Out |
| 12 | Ease In |
| 13 | Ease Out |
| 14 | Quadratic Ease In |
| 15 | Quadratic Ease Out |
| 16 | Quadratic Ease In Out |
| 17 | Cubic Ease In |
| 18 | Cubic Ease Out |
| 19 | Cubic Ease In Out |
| 20 | Quartic Ease In |
| 21 | Quartic Ease Out |
| 22 | Quartic Ease In Out |
| 23 | Quintic Ease In |
| 24 | Quintic Ease Out |
| 25 | Quintic Ease In Out |
| 26 | Circular Ease In |
| 27 | Circular Ease Out |
| 28 | Circular Ease In Out |
| 29 | Max (The Maximum Number Of Graph Types, Do Not Use.) |


## Parameters
* **camera**: 
* **camera**: 
* **Duration**: The time of the tinterp in milli seconds.
* **GraphTypePos**: 
* **GraphTypeRot**: 
