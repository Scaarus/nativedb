---
ns: CAMERA
aliases: ["0x19cafa3c87f7c2ff"]
---
## GET_CAM_ACTIVE_VIEW_MODE_CONTEXT

```c
// 0x19CAFA3C87F7C2FF
cam_view_mode_context GET_CAM_ACTIVE_VIEW_MODE_CONTEXT();
```

```
Returns the view mode context for the active gameplay camera. This may then be used with commands such as GET_CAM_VIEW_MODE_FOR_CONTEXT and SET_CAM_VIEW_MODE_FOR_CONTEXT. See CAM_VIEW_MODE_CONTEXT enumeration.

Possible return values:
| Index | Name |
| --- | --- |
| 0 | CAM_VIEW_MODE_CONTEXT_ON_FOOT |
| 30 | CAM_VIEW_MODE_CONTEXT_IN_VEHICLE |
| 31 | CAM_VIEW_MODE_CONTEXT_ON_BIKE |
| 32 | CAM_VIEW_MODE_CONTEXT_IN_BOAT |
| 33 | CAM_VIEW_MODE_CONTEXT_IN_AIRCRAFT |
| 34 | CAM_VIEW_MODE_CONTEXT_IN_SUBMARINE |
| 35 | CAM_VIEW_MODE_CONTEXT_IN_HELI |
| 36 | CAM_VIEW_MODE_CONTEXT_IN_TURRET |
| 37 | NUM_CAM_VIEW_MODE_CONTEXTS |
```
