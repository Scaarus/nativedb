---
ns: CAMERA
aliases: ["0x487a82c650eb7799"]
---
## SET_GAMEPLAY_CAM_MOTION_BLUR_SCALING_THIS_UPDATE

```c
// 0x487A82C650EB7799
void SET_GAMEPLAY_CAM_MOTION_BLUR_SCALING_THIS_UPDATE(float scaling);
```

```
Sets the script-controlled motion blur scaling to be applied within the active gameplay camera this update (only.) Note that this command must be called every update that scaling is required, as this parameter automatically resets for safety.
```

## Parameters
* **scaling**: The scaling factor to be applied to the current motion blur strength, with a value of 1.0 resulting in no change.
