---
ns: CAMERA
aliases: ["0x48608c3464f58ab4"]
---
## FORCE_CAMERA_RELATIVE_HEADING_AND_PITCH

```c
// 0x48608C3464F58AB4
void FORCE_CAMERA_RELATIVE_HEADING_AND_PITCH(float heading, float pitch, float pitchSmoothRate);
```

Force the gameplay and cinematic mounted camera's heading and pitch relative to the target entity (ped or vehicle).


## Parameters
* **heading**: The relative heading to set, in degrees. (Default value: `0`)
* **pitch**: The relative pitch to set, in degrees. (Default value: `0`)
* **pitchSmoothRate**: (Default value: `1`)
