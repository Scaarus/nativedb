---
ns: CAMERA
aliases: ["0x7d304c1c955e3e12"]
---
## GET_CAM_ROT

```c
// 0x7D304C1C955E3E12
Vector3 GET_CAM_ROT(Camera camera, int RotOrder);
```

Get the camera's rotation in Euler angles (in degrees.)

## Values for `RotOrder`:
| Value | Name |
| --- | --- |
| 0 | Xyz |
| 1 | Xzy |
| 2 | Yxz |
| 3 | Yzx |
| 4 | Zxy |
| 5 | Zyx |


## Parameters
* **camera**: 
* **RotOrder**: (Default value: `Yxz`)
