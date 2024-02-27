---
ns: CAMERA
aliases: ["0xee778f8c7e1142e2"]
---
## GET_CAM_VIEW_MODE_FOR_CONTEXT

```c
// 0xEE778F8C7E1142E2
int GET_CAM_VIEW_MODE_FOR_CONTEXT(int Context);
```

Gets the camera view mode for the specified context.

## Return Type Values:
| Value | Name |
| --- | --- |
| 0 | Third Person Near |
| 1 | Third Person Medium |
| 2 | Third Person Far |
| 3 | Cinematic |
| 4 | First Person |
| 6 | Third Person |

## Values for `Context`:
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


## Parameters
* **Context**: The view mode context to be queried. See CAM_VIEW_MODE_CONTEXT enumeration.
