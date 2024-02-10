---
ns: CAMERA
aliases: ["0xf55e4046f6f831dc"]
---
## SET_CAM_DOF_OVERRIDDEN_FOCUS_DISTANCE

```c
// 0xF55E4046F6F831DC
void SET_CAM_DOF_OVERRIDDEN_FOCUS_DISTANCE(Camera camera, float distance);
```

```
Specifies a custom focus distance (in metres) that should be used by the adaptive depth of field effect, overriding of any other focus behaviour. Note that this override is blended relative to the measured depth via SET_CAM_DOF_OVERRIDDEN_FOCUS_DISTANCE_BLEND_LEVEL.

The valid range of 'distance' is 0.0 to 99999.0.
```
