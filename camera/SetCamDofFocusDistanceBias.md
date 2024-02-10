---
ns: CAMERA
aliases: ["0xc669eea5d031b7de"]
---
## SET_CAM_DOF_FOCUS_DISTANCE_BIAS

```c
// 0xC669EEA5D031B7DE
void SET_CAM_DOF_FOCUS_DISTANCE_BIAS(Camera camera, float distanceBias);
```

Specifies an offset to be applied to the focus distance (in metres.) This is especially useful for adjusting the focus point on a look-at or attach entity that is being focussed upon.

The valid range of 'distanceBias' is -100.0 to 100.0.

