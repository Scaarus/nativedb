---
ns: CAMERA
aliases: ["0x33e6c8efd0cd93e9"]
---
## GET_FOLLOW_PED_CAM_ZOOM_LEVEL

```c
// 0x33E6C8EFD0CD93E9
int GET_FOLLOW_PED_CAM_ZOOM_LEVEL();
```

Gets the global zoom level used by all follow-ped cameras

## Return Type Values:
| Value | Name |
| --- | --- |
| -1 | Bad |
| 0 | Near |
| 1 | Medium |
| 2 | Far |
| 3 | Cinematic |
| 4 | First Person |

Deprecated! Please now use [`GET_FOLLOW_PED_CAM_VIEW_MODE`](#_0x8D4D46230B2C353A)

