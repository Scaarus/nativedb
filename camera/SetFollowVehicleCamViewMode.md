---
ns: CAMERA
aliases: ["0xac253d7842768f48"]
---
## SET_FOLLOW_VEHICLE_CAM_VIEW_MODE

```c
// 0xAC253D7842768F48
void SET_FOLLOW_VEHICLE_CAM_VIEW_MODE(int ViewMode);
```

Sets the view mode used by the follow-vehicle and vehicle-aim cameras associated with classes of vehicles that are not handled specially, such as cars. Use [SET_CAM_VIEW_MODE_FOR_CONTEXT](#_0x2A2173E46DAECD12) to set the view mode applied for other classes of vehicle.

## ViewMode Values:
| Value | Name |
| --- | --- |
| 0 | Third Person Near |
| 1 | Third Person Medium |
| 2 | Third Person Far |
| 3 | Cinematic |
| 4 | First Person |
| 6 | Third Person |

