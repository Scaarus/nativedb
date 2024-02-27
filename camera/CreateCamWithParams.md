---
ns: CAMERA
aliases: ["0xb51194800b257161"]
---
## CREATE_CAM_WITH_PARAMS

```c
// 0xB51194800B257161
Camera CREATE_CAM_WITH_PARAMS(string CameraName, Vector3 vecPos, Vector3 vecRot, bool StartActivated, int RotOrder);
```

Create a camera with its param of a given name.

## RotOrder Values:
| Value | Name |
| --- | --- |
| 0 | Xyz |
| 1 | Xzy |
| 2 | Yxz |
| 3 | Yzx |
| 4 | Zxy |
| 5 | Zyx |


Valid camera names are as


## Parameters
* **CameraName**: 
* **vecPos**: 
* **vecRot**: 
* **StartActivated**: (Default value: `False`)
* **RotOrder**: (Default value: `Yxz`)
