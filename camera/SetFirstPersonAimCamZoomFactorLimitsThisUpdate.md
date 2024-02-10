---
ns: CAMERA
aliases: ["0xced08cbe8ebb97c7"]
---
## SET_FIRST_PERSON_AIM_CAM_ZOOM_FACTOR_LIMITS_THIS_UPDATE

```c
// 0xCED08CBE8EBB97C7
void SET_FIRST_PERSON_AIM_CAM_ZOOM_FACTOR_LIMITS_THIS_UPDATE(float MinZoomFactor, float MaxZoomFactor);
```

Sets the minimum and maximum zoom factor that can be applied for the active first-person aim camera for this update only.

Please note that the specified zoom factor limits will be clamped to between 1.0 and the maximum zoom factor supported by the specific weapon/camera.

