---
ns: CAMERA
aliases: ["0x0a9f2a468b328e74"]
---
## ADD_CAM_SPLINE_NODE_USING_CAMERA_FRAME

```c
// 0x0A9F2A468B328E74
void ADD_CAM_SPLINE_NODE_USING_CAMERA_FRAME(Camera camera, Camera camera, int iDuration, int Flags);
```

```
Appends a full node on to a spline camera. The frame parameters of this new node are cloned from an existing scripted camera.

Possible values for Flags:
| Index | Name |
| --- | --- |
| 0 | No Flags |
| 1 | Smooth Rot |
| 2 | Smooth Lens Params |
| 4 | Ease In |
| 8 | Ease Out |
| 16 | Ease Inout |
```

## Parameters
* **camera**: 
* **camera**: 
* **iDuration**: The time taken to transition from the previous node to this node, in milliseconds.
* **Flags**: Defines custom options to be applied to this node. See definition of CAM_SPLINE_NODE_FLAGS for more info.
