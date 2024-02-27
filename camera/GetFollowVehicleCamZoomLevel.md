---
ns: CAMERA
aliases: ["0xee82280ab767b690"]
---
## GET_FOLLOW_VEHICLE_CAM_ZOOM_LEVEL

```c
// 0xEE82280AB767B690
int GET_FOLLOW_VEHICLE_CAM_ZOOM_LEVEL();
```

Gets the global zoom level used by all follow-vehicle and vehicle-aim cameras.

## Return Type Values:
| Value | Name |
| --- | --- |
| -1 | Bad |
| 0 | Near |
| 1 | Medium |
| 2 | Far |
| 3 | Cinematic |
| 4 | Bonnet |

Deprecated! Please now use [`GET_FOLLOW_VEHICLE_CAM_VIEW_MODE`](#_0xA4FF579AC0E3AAAE)

