---
ns: CAMERA
aliases: ["0x83b8201ed82a9a2d"]
---
## SET_CAM_SPLINE_NODE_EASE

```c
// 0x83B8201ED82A9A2D
void SET_CAM_SPLINE_NODE_EASE(Camera camera, int NodeIndex, int Flags, float Scale);
```

Set per-node easing with a scaler to control how quickly the ease ramps up/down.

## Values for `Flags`:
| Value | Name |
| --- | --- |
| 0 | No Flags |
| 1 | Smooth Rot |
| 2 | Smooth Lens Params |
| 4 | Ease In |
| 8 | Ease Out |
| 16 | Ease Inout |


Nodes must be setup first, then the linear flag can be modified.


## Parameters
* **camera**: 
* **NodeIndex**: 
* **Flags**: 
* **Scale**: (Default value: `1`)
