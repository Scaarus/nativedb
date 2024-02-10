---
ns: CAMERA
aliases: ["0x5a4f9edf1673f704"]
---
## SET_FOLLOW_PED_CAM_VIEW_MODE

```c
// 0x5A4F9EDF1673F704
void SET_FOLLOW_PED_CAM_VIEW_MODE(int ViewMode);
```

```
Sets the global view mode used by all follow-ped cameras. Please note that the first-person and cinematic view modes are presently not supported by the follow-ped cameras.

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
