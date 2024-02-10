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
| -1 | VEHICLE_ZOOM_LEVEL_BAD |
| 50 | VEHICLE_ZOOM_LEVEL_NEAR |
| 51 | VEHICLE_ZOOM_LEVEL_MEDIUM |
| 52 | VEHICLE_ZOOM_LEVEL_FAR |
| 53 | VEHICLE_ZOOM_LEVEL_CINEMATIC |
| 54 | VEHICLE_ZOOM_LEVEL_BONNET |
| 55 | NUM_VEHICLE_ZOOM_LEVELS |


Deprecated! Please now use SET_FOLLOW_VEHICLE_CAM_VIEW_MODE

