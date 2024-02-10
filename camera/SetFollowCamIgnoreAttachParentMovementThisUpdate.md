---
ns: CAMERA
aliases: ["0xdd79df9f4d26e1c9"]
---
## SET_FOLLOW_CAM_IGNORE_ATTACH_PARENT_MOVEMENT_THIS_UPDATE

```c
// 0xDD79DF9F4D26E1C9
void SET_FOLLOW_CAM_IGNORE_ATTACH_PARENT_MOVEMENT_THIS_UPDATE();
```

Forces the active follow camera to ignore the movement of the attach parent when computing the follow orientation this update. (only) The follow camera will then rotate based upon control input only, similar to an aim camera. This setting automatically resets for safety.

