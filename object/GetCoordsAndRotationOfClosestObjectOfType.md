---
ns: OBJECT
aliases: ["0x163f8b586bc95f2a"]
---
## GET_COORDS_AND_ROTATION_OF_CLOSEST_OBJECT_OF_TYPE

```c
// 0x163F8B586BC95F2A
bool GET_COORDS_AND_ROTATION_OF_CLOSEST_OBJECT_OF_TYPE(Vector3 SphereCentre, float fSphereRadius, Hash modelHash, Vector3 ReturnCoords, Vector3 ReturnRotation, int RotOrder);
```

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
* **SphereCentre**: 
* **fSphereRadius**: 
* **modelHash**: 
* **ReturnCoords**: 
* **ReturnRotation**: 
* **RotOrder**: (Default value: `Yxz`)
