---
ns: CAMERA
aliases: ["0xbfd8727aea3cceba"]
---
## SET_CAM_PARAMS

```c
// 0xBFD8727AEA3CCEBA
void SET_CAM_PARAMS(Camera camera, Vector3 vPos, Vector3 vRot, float FOV, int Duration, int GraphTypePos, int GraphTypeRot, int RotOrder);
```

Sets the camera's position, rotation and field of view.

## Values for `GraphTypePos`:
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


## Values for `RotOrder`:
| Value | Name |
| --- | --- |
| 0 | Xyz |
| 1 | Xzy |
| 2 | Yxz |
| 3 | Yzx |
| 4 | Zxy |
| 5 | Zyx |


If duration is set > 0 the camera will interp to the specified settings.


## Parameters
* **camera**: 
* **vPos**: 
* **vRot**: 
* **FOV**: 
* **Duration**: (Default value: `0`)
* **GraphTypePos**: (Default value: `Graph_Type_Sin_Accel_Decel`)
* **GraphTypeRot**: (Default value: `Graph_Type_Sin_Accel_Decel`)
* **RotOrder**: (Default value: `Yxz`)
