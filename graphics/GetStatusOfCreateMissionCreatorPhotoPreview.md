---
ns: GRAPHICS
aliases: ["0x5b0316762afd4a64"]
---
## GET_STATUS_OF_CREATE_MISSION_CREATOR_PHOTO_PREVIEW

```c
// 0x5B0316762AFD4A64
photo_operation_status GET_STATUS_OF_CREATE_MISSION_CREATOR_PHOTO_PREVIEW();
```

Returns the status of the request triggered by BEGIN_CREATE_MISSION_CREATOR_PHOTO_PREVIEW Once this preview is ready, it can be used by script or scaleform. Both the name of the TXD and the texture is always "MISSION_CREATOR_TEXTURE"

## Return Type Values:
| Value | Name |
| --- | --- |
| 19 | Succeeded |
| 20 | In Progress |
| 21 | Failed |

