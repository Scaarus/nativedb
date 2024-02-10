---
ns: CAMERA
aliases: ["0x7dcf7c708d292d55"]
---
## OVERRIDE_CAM_SPLINE_MOTION_BLUR

```c
// 0x7DCF7C708D292D55
void OVERRIDE_CAM_SPLINE_MOTION_BLUR(Camera camera, int Entry, float BlurStart, float MotionBlur);
```

```
Sets an entry with the speed of specified "time" and when (as a percentage) the spline should blend from that speed to the next node's speed.

Nodes must be setup first before this is called. (Note: have to override all nodes in the spline)
```
