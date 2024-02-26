---
ns: CAMERA
aliases: ["0xa4ff579ac0e3aaae"]
---
## GET_FOLLOW_VEHICLE_CAM_VIEW_MODE

```c
// 0xA4FF579AC0E3AAAE
int GET_FOLLOW_VEHICLE_CAM_VIEW_MODE();
```

Gets the view mode used by the follow-vehicle and vehicle-aim cameras associated with classes of vehicles that are not handled specially, such as cars. Use [GET_CAM_VIEW_MODE_FOR_CONTEXT](#_0xEE778F8C7E1142E2) to query the view mode applied for other classes of vehicle.

## Return Type Values:
| Value | Name |
| --- | --- |
| 0 | Third Person Near |
| 1 | Third Person Medium |
| 2 | Third Person Far |
| 3 | Cinematic |
| 4 | First Person |
| 6 | Third Person |

