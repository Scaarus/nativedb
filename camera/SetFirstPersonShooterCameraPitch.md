---
ns: CAMERA
aliases: ["0x759e13ebc1c15c5a"]
---
## SET_FIRST_PERSON_SHOOTER_CAMERA_PITCH

```c
// 0x759E13EBC1C15C5A
void SET_FIRST_PERSON_SHOOTER_CAMERA_PITCH(float pitch);
```

Sets the first person shooter camera pitch. If the camera does not exist, this pitch will be used when it is created.

If the first person shooter camera is active, does the same thing as [SET_GAMEPLAY_CAM_RELATIVE_PITCH](#_0x6D0858B8EDFD2B7D). If not active, the pitch will be set when the camera is created.


## Parameters
* **pitch**: The relative pitch to set, in degrees.
