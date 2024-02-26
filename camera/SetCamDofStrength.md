---
ns: CAMERA
aliases: ["0x5ee29b4d7d5df897"]
---
## SET_CAM_DOF_STRENGTH

```c
// 0x5EE29B4D7D5DF897
void SET_CAM_DOF_STRENGTH(Camera camera, float Strength);
```

Set the 'strength' of the camera's depth of field effect (0.0 to 1.0.)

Note that this command nulls the effect of any previous call to [SET_CAM_DOF_PLANES](#_0x3CF48F6F96E749DC), as the out-of-focus DOF planes will henceforth be derived based upon the DOF strength.

