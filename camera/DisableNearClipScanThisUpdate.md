---
ns: CAMERA
aliases: ["0x5a43c76f7fc7ba5f"]
---
## DISABLE_NEAR_CLIP_SCAN_THIS_UPDATE

```c
// 0x5A43C76F7FC7BA5F
void DISABLE_NEAR_CLIP_SCAN_THIS_UPDATE();
```

Disables the (PS3-specific) scanning near-clip for this update only. This prevents the final rendered near-clip distance from being increased automatically when the extended frustum in front of the camera is free of collision. Note that use of this command may result in increased z-fighting on PS3, as the scanning near-clip is designed to reduce this.

