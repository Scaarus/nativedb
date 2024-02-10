---
ns: CAMERA
aliases: ["0xee82280ab767b690"]
---
## GET_FOLLOW_VEHICLE_CAM_ZOOM_LEVEL

```c
// 0xEE82280AB767B690
vehicle_zoom_level GET_FOLLOW_VEHICLE_CAM_ZOOM_LEVEL();
```

```
Gets the global zoom level used by all follow-vehicle and vehicle-aim cameras.

Possible return values:
| Index | Name |
| --- | --- |
| -1 | VEHICLE_ZOOM_LEVEL_BAD |
| 50 | VEHICLE_ZOOM_LEVEL_NEAR |
| 51 | VEHICLE_ZOOM_LEVEL_MEDIUM |
| 52 | VEHICLE_ZOOM_LEVEL_FAR |
| 53 | VEHICLE_ZOOM_LEVEL_CINEMATIC |
| 54 | VEHICLE_ZOOM_LEVEL_BONNET |
| 55 | NUM_VEHICLE_ZOOM_LEVELS |


Deprecated! Please now use GET_FOLLOW_VEHICLE_CAM_VIEW_MODE
```
