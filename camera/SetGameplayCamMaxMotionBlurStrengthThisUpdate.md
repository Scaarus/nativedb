---
ns: CAMERA
aliases: ["0x0225778816fdc28c"]
---
## SET_GAMEPLAY_CAM_MAX_MOTION_BLUR_STRENGTH_THIS_UPDATE

```c
// 0x0225778816FDC28C
void SET_GAMEPLAY_CAM_MAX_MOTION_BLUR_STRENGTH_THIS_UPDATE(float maxStrength);
```

Sets the script-controlled maximum motion blur strength to be applied within the active gameplay camera this update (only.) Note that this command must be called every update that limiting is required, as this parameter automatically resets for safety.


## Parameters
* **maxStrength**: The maximum motion blur strength to be applied. This value is clamped to the valid range of 0.0 to 1.0 in code.
