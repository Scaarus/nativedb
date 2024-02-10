---
ns: CAMERA
aliases: ["0x47b595d60664cffa"]
---
## SET_CAM_DOF_FOCAL_LENGTH_MULTIPLIER

```c
// 0x47B595D60664CFFA
void SET_CAM_DOF_FOCAL_LENGTH_MULTIPLIER(Camera camera, float multiplier);
```

```
Specifies the focal length multiplier to be used by the physical lens model in the adaptive depth of field effect. This is equivalent to crop factor. Increasing this value will result in shallower depth of field and stonger blur.

The valid range of 'multiplier' is 0.1 to 10.0.
```
