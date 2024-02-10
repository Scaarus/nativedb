---
ns: CAMERA
aliases: ["0xd1b0f412f109ea5d"]
---
## SET_CAM_SPLINE_SMOOTHING_STYLE

```c
// 0xD1B0F412F109EA5D
void SET_CAM_SPLINE_SMOOTHING_STYLE(Camera camera, int SmoothingStyle);
```

Sets the smoothing style of the spline camera at the spline nodes.

## SmoothingStyle Values:
| Value | Name |
| --- | --- |
| 0 | No Smooth |
| 1 | Slow In Smooth |
| 2 | Slow Out Smooth |
| 3 | Slow In Out Smooth |
| 4 | Very Slow In |
| 5 | Very Slow Out |
| 6 | Very Slow In Slow Out |
| 7 | Slow In Very Slow Out |
| 8 | Very Slow In Very Slow Out |
| 9 | Ease In |
| 10 | Ease Out |
| 11 | Quadratic Ease In |
| 12 | Quadratic Ease Out |
| 13 | Quadratic Ease In Out |
| 14 | Cubic Ease In |
| 15 | Cubic Ease Out |
| 16 | Cubic Ease In Out |
| 17 | Quartic Ease In |
| 18 | Quartic Ease Out |
| 19 | Quartic Ease In Out |
| 20 | Quintic Ease In |
| 21 | Quintic Ease Out |
| 22 | Quintic Ease In Out |
| 23 | Circular Ease In |
| 24 | Circular Ease Out |
| 25 | Circular Ease In Out |


CAM_SPLINE_NO_SMOOTHING = 0, No smoothing just moves at a constant rate CAM_SPLINE_SLOW_IN = 1, Decelerates when approaching a node CAM_SPLINE_SLOW_OUT =2, Accelerates slowly when leaving a node CAM_SPLINE_SLOW_IN_OUT =3 Decelerates when approaching a node and accelerates slowly when leaving a node

