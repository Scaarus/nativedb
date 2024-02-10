---
ns: CAMERA
aliases: ["0xac253d7842768f48"]
---
## SET_FOLLOW_VEHICLE_CAM_VIEW_MODE

```c
// 0xAC253D7842768F48
void SET_FOLLOW_VEHICLE_CAM_VIEW_MODE(int ViewMode);
```

```
Sets the view mode used by the follow-vehicle and vehicle-aim cameras associated with classes of vehicles that are not handled specially, such as cars. Use SET_CAM_VIEW_MODE_FOR_CONTEXT to set the view mode applied for other classes of vehicle.

Possible values for ViewMode:
| Index | Name |
| --- | --- |
| 0 | CAM_VIEW_MODE_THIRD_PERSON_NEAR |
| 38 | CAM_VIEW_MODE_THIRD_PERSON_MEDIUM |
| 39 | CAM_VIEW_MODE_THIRD_PERSON_FAR |
| 40 | CAM_VIEW_MODE_CINEMATIC |
| 41 | CAM_VIEW_MODE_FIRST_PERSON |
| 42 | NUM_CAM_VIEW_MODES |
| 43 | CAM_VIEW_MODE_THIRD_PERSON |
```
