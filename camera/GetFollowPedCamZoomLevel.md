---
ns: CAMERA
aliases: ["0x33e6c8efd0cd93e9"]
---
## GET_FOLLOW_PED_CAM_ZOOM_LEVEL

```c
// 0x33E6C8EFD0CD93E9
ped_zoom_level GET_FOLLOW_PED_CAM_ZOOM_LEVEL();
```

Gets the global zoom level used by all follow-ped cameras

## Return Type Values:
| Value | Name |
| --- | --- |
| -1 | PED_ZOOM_LEVEL_BAD |
| 44 | PED_ZOOM_LEVEL_NEAR |
| 45 | PED_ZOOM_LEVEL_MEDIUM |
| 46 | PED_ZOOM_LEVEL_FAR |
| 47 | PED_ZOOM_LEVEL_CINEMATIC |
| 48 | PED_ZOOM_LEVEL_FIRST_PERSON |
| 49 | NUM_PED_ZOOM_LEVELS |


Deprecated! Please now use GET_FOLLOW_PED_CAM_VIEW_MODE

