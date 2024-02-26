---
ns: CAMERA
aliases: ["0x5a4f9edf1673f704"]
---
## SET_FOLLOW_PED_CAM_VIEW_MODE

```c
// 0x5A4F9EDF1673F704
void SET_FOLLOW_PED_CAM_VIEW_MODE(int ViewMode);
```

Sets the global view mode used by all follow-ped cameras. Please note that the first-person and cinematic view modes are presently not supported by the follow-ped cameras.

## ViewMode Values:
| Value | Name |
| --- | --- |
| 0 | Third Person Near |
| 1 | Third Person Medium |
| 2 | Third Person Far |
| 3 | Cinematic |
| 4 | First Person |
| 6 | Third Person |

