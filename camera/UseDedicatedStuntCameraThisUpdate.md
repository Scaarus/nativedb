---
ns: CAMERA
aliases: ["0x425a920fdb9a0dda"]
---
## USE_DEDICATED_STUNT_CAMERA_THIS_UPDATE

```c
// 0x425A920FDB9A0DDA
void USE_DEDICATED_STUNT_CAMERA_THIS_UPDATE(string stuntCamera);
```

```
Similar to USE_VEHICLE_CAM_STUNT_SETTINGS_THIS_UPDATE, but instead it uses a dedicated camera and not a group of settings. The system will still try to detect if the stunt camera is needed based by the vehicle orientation.
```

## Parameters
* **stuntCamera**: the camera name to use (normally you want to use FOLLOW_VEHICLE_STUNT_CAMERA)
