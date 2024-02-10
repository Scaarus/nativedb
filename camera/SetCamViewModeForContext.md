---
ns: CAMERA
aliases: ["0x2a2173e46daecd12"]
---
## SET_CAM_VIEW_MODE_FOR_CONTEXT

```c
// 0x2A2173E46DAECD12
void SET_CAM_VIEW_MODE_FOR_CONTEXT(int Context, int ViewMode);
```

```
Sets the camera view mode for the specified context.

Possible values for Context:
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

## Parameters
* **Context**: The view mode context to be configured. See CAM_VIEW_MODE_CONTEXT enumeration.
* **ViewMode**: The view mode to be applied. See CAM_VIEW_MODE enumeration.
