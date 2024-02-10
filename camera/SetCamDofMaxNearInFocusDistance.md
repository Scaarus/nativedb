---
ns: CAMERA
aliases: ["0xc3654a441402562d"]
---
## SET_CAM_DOF_MAX_NEAR_IN_FOCUS_DISTANCE

```c
// 0xC3654A441402562D
void SET_CAM_DOF_MAX_NEAR_IN_FOCUS_DISTANCE(Camera camera, float distance);
```

```
Specifies how far the foreground blur is allowed to render ahead of the camera (in metres.) Note that this limit is blended in via SET_CAM_DOF_MAX_NEAR_IN_FOCUS_DISTANCE_BLEND_LEVEL.

The valid range of 'distance' is 0.0 to 99999.0.
```
