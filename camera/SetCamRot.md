---
ns: CAMERA
aliases: ["0x85973643155d0b07"]
---
## SET_CAM_ROT

```c
// 0x85973643155D0B07
void SET_CAM_ROT(Camera camera, Vector3 NewRot, int RotOrder);
```

```
Set the camera's rotation in Euler angles (in degrees.)

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
