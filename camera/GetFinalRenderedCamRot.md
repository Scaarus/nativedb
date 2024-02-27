---
ns: CAMERA
aliases: ["0x5b4e4c817fcc2dfb"]
---
## GET_FINAL_RENDERED_CAM_ROT

```c
// 0x5B4E4C817FCC2DFB
Vector3 GET_FINAL_RENDERED_CAM_ROT(int RotOrder);
```

Gets the rotation of the final rendered cam.

## RotOrder Values:
| Value | Name |
| --- | --- |
| 0 | Xyz |
| 1 | Xzy |
| 2 | Yxz |
| 3 | Yzx |
| 4 | Zxy |
| 5 | Zyx |


## Parameters
* **RotOrder**: (Default value: `Yxz`)
