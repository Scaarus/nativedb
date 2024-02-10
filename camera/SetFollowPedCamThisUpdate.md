---
ns: CAMERA
aliases: ["0x44a113dd6ffc48d1"]
---
## SET_FOLLOW_PED_CAM_THIS_UPDATE

```c
// 0x44A113DD6FFC48D1
bool SET_FOLLOW_PED_CAM_THIS_UPDATE(string CameraName, int InterpolationDuration);
```

```
Overrides the follow-ped camera on this update only. Returns TRUE if successful.

Can be safely called at any time, but will only have a visible effect when a follow-ped gameplay camera is rendering.
```

## Parameters
* **CameraName**: The name of the custom camera to be used. This command will assert and return FALSE if this name is not valid.
* **InterpolationDuration**: The duration of the interpolation in and out of the custom camera, so long as it is blending tofrom a follow-ped camera. Standard interpolation behaviour applies for other camera transitions.
