---
ns: CAMERA
aliases: ["0x8609c75ec438fb3b"]
---
## ADD_CAM_SPLINE_NODE

```c
// 0x8609C75EC438FB3B
void ADD_CAM_SPLINE_NODE(Camera camera, Vector3 vPos, Vector3 vRot, int iDuration, int Flags, int RotOrder);
```

Appends a simple node on to a spline camera.

## Flags Values:
| Value | Name |
| --- | --- |
| 0 | No Flags |
| 1 | Smooth Rot |
| 2 | Smooth Lens Params |
| 4 | Ease In |
| 8 | Ease Out |
| 16 | Ease Inout |


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
* **camera**: 
* **vPos**: The position of the node in world-space.
* **vRot**: The rotationorientation of the node in Euler angles (in degrees.)
* **iDuration**: The time taken to transition from the previous node to this node, in milliseconds.
* **Flags**: Defines custom options to be applied to this node. See definition of CAM_SPLINE_NODE_FLAGS for more info.
* **RotOrder**: 
