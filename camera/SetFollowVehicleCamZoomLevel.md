---
ns: CAMERA
aliases: ["0x19464cb6e4078c8a"]
---
## SET_FOLLOW_VEHICLE_CAM_ZOOM_LEVEL

```c
// 0x19464CB6E4078C8A
void SET_FOLLOW_VEHICLE_CAM_ZOOM_LEVEL(int ZoomLevel);
```

Sets the global zoom level used by all follow-vehicle and vehicle-aim cameras.

## ZoomLevel Values:
| Value | Name |
| --- | --- |
| -1 | Bad |
| 0 | Near |
| 1 | Medium |
| 2 | Far |
| 3 | Cinematic |
| 4 | Bonnet |


Deprecated! Please now use [SET_FOLLOW_VEHICLE_CAM_VIEW_MODE](#_0xAC253D7842768F48)

