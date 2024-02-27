---
ns: CAMERA
aliases: ["0x3cf48f6f96e749dc"]
---
## SET_CAM_DOF_PLANES

```c
// 0x3CF48F6F96E749DC
void SET_CAM_DOF_PLANES(Camera camera, float nearOutOfFocusPlane, float nearInFocusPlane, float farInFocusPlane, float farOutOfFocusPlane);
```

Set the distances of the four planes for the camera's depth of field effect (in m.)

Note that this command nulls the effect of any previous call to [`SET_CAM_DOF_STRENGTH`](#_0x5EE29B4D7D5DF897), as the four DOF planes are overwritten and the relationship between the out-of-focus planes and the DOF strength is broken.

