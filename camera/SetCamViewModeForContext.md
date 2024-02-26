---
ns: CAMERA
aliases: ["0x2a2173e46daecd12"]
---
## SET_CAM_VIEW_MODE_FOR_CONTEXT

```c
// 0x2A2173E46DAECD12
void SET_CAM_VIEW_MODE_FOR_CONTEXT(int Context, int ViewMode);
```

Sets the camera view mode for the specified context.

## Context Values:
| Value | Name |
| --- | --- |
| 0 | On Foot |
| 1 | In Vehicle |
| 2 | On Bike |
| 3 | In Boat |
| 4 | In Aircraft |
| 5 | In Submarine |
| 6 | In Heli |
| 7 | In Turret |


## ViewMode Values:
| Value | Name |
| --- | --- |
| 0 | Third Person Near |
| 1 | Third Person Medium |
| 2 | Third Person Far |
| 3 | Cinematic |
| 4 | First Person |
| 6 | Third Person |


## Parameters
* **Context**: The view mode context to be configured. See CAM_VIEW_MODE_CONTEXT enumeration.
* **ViewMode**: The view mode to be applied. See CAM_VIEW_MODE enumeration.
