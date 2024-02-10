---
ns: CAMERA
aliases: ["0xa4ff579ac0e3aaae"]
---
## GET_FOLLOW_VEHICLE_CAM_VIEW_MODE

```c
// 0xA4FF579AC0E3AAAE
cam_view_mode GET_FOLLOW_VEHICLE_CAM_VIEW_MODE();
```

```
Gets the view mode used by the follow-vehicle and vehicle-aim cameras associated with classes of vehicles that are not handled specially, such as cars. Use GET_CAM_VIEW_MODE_FOR_CONTEXT to query the view mode applied for other classes of vehicle.

Possible return values:
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
