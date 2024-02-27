---
ns: CAMERA
aliases: ["0x0fb82563989cf4fb"]
---
## ADD_CAM_SPLINE_NODE_USING_CAMERA

```c
// 0x0FB82563989CF4FB
void ADD_CAM_SPLINE_NODE_USING_CAMERA(Camera camera, Camera camera, int iDuration, int Flags);
```

Appends a full node on to a spline camera. The frame parameters of this new node are cloned from an existing scripted camera.

## Values for `Flags`:
| Value | Name |
| --- | --- |
| 0 | No Flags |
| 1 | Smooth Rot |
| 2 | Smooth Lens Params |
| 4 | Ease In |
| 8 | Ease Out |
| 16 | Ease Inout |


## Parameters
* **camera**: 
* **camera**: 
* **iDuration**: The time taken to transition from the previous node to this node, in milliseconds.
* **Flags**: Defines custom options to be applied to this node. See definition of CAM_SPLINE_NODE_FLAGS for more info. (Default value: `Default_Cam_Spline_Node_Flags`)
