---
ns: CAMERA
aliases: ["0x6d0858b8edfd2b7d"]
---
## SET_GAMEPLAY_CAM_RELATIVE_PITCH

```c
// 0x6D0858B8EDFD2B7D
void SET_GAMEPLAY_CAM_RELATIVE_PITCH(float pitch, float smoothRate);
```

Sets the gameplay camera's pitch relative to the target entity (ped or vehicle.)

This won't work for vehicles POVs, if you need to change the camera pitch and want the change on vehicle's POVs as well, please use [`FORCE_CAMERA_RELATIVE_HEADING_AND_PITCH`](#_0x48608C3464F58AB4).


## Parameters
* **pitch**: The relative pitch to set, in degrees. (Default value: `0`)
* **smoothRate**: The rate at which the relative pitch should be attained. 1.0 is instant, 0.0 is infinite. (Default value: `1`)
