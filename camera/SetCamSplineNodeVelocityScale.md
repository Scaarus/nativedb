---
ns: CAMERA
aliases: ["0xa6385deb180f319f"]
---
## SET_CAM_SPLINE_NODE_VELOCITY_SCALE

```c
// 0xA6385DEB180F319F
void SET_CAM_SPLINE_NODE_VELOCITY_SCALE(Camera camera, int NodeIndex, float Scale);
```

By default, scale is zero, so disabled. Set value between -1.0 and 1.0 to modify the velocity and change the shape of the spline.

Nodes must be setup first before this is called. Linearly interpolates between previous and next node's velocity. Disabled if zero.

