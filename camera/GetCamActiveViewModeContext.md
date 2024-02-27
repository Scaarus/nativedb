---
ns: CAMERA
aliases: ["0x19cafa3c87f7c2ff"]
---
## GET_CAM_ACTIVE_VIEW_MODE_CONTEXT

```c
// 0x19CAFA3C87F7C2FF
int GET_CAM_ACTIVE_VIEW_MODE_CONTEXT();
```

Returns the view mode context for the active gameplay camera. This may then be used with commands such as [`GET_CAM_VIEW_MODE_FOR_CONTEXT`](#_0xEE778F8C7E1142E2) and [`SET_CAM_VIEW_MODE_FOR_CONTEXT`](#_0x2A2173E46DAECD12). See CAM_VIEW_MODE_CONTEXT enumeration.

## Return Type Values:
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

