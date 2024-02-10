---
ns: CAMERA
aliases: ["0x70894bd0915c5bca"]
---
## SET_FIRST_PERSON_AIM_CAM_ZOOM_FACTOR

```c
// 0x70894BD0915C5BCA
void SET_FIRST_PERSON_AIM_CAM_ZOOM_FACTOR(float ZoomFactor);
```

Sets the first-person aim zoom factor associated with equipped scoped weapon, or the mobile phone camera, if active.

Please note that the specified zoom factor will be clamped to between 1.0 and the maximum zoom factor supported by the specific weaponcamera. The zoom factor will also automatically reset to 1.0 if the follow ped's equipped weapon changes or the mobile phone camera toggles on or off.

