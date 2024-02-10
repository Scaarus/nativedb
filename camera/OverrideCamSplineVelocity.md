---
ns: CAMERA
aliases: ["0x40b62fa033eb0346"]
---
## OVERRIDE_CAM_SPLINE_VELOCITY

```c
// 0x40B62FA033EB0346
void OVERRIDE_CAM_SPLINE_VELOCITY(Camera camera, int Entry, float StartPoint, float Speed);
```

Sets an entry with the speed of specified "time" and when (as a percentage) the spline should blend from that speed to the next node's speed.

Nodes must be setup first before this is called. (Note: have to override all nodes in the spline)

