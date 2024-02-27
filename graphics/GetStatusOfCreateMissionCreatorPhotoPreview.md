---
ns: GRAPHICS
aliases: ["0x5b0316762afd4a64"]
---
## GET_STATUS_OF_CREATE_MISSION_CREATOR_PHOTO_PREVIEW

```c
// 0x5B0316762AFD4A64
int GET_STATUS_OF_CREATE_MISSION_CREATOR_PHOTO_PREVIEW();
```

Returns the status of the request triggered by [`BEGIN_CREATE_MISSION_CREATOR_PHOTO_PREVIEW`](#_0x7FA5D82B8F58EC06) Once this preview is ready, it can be used by script or scaleform. Both the name of the TXD and the texture is always "MISSION_CREATOR_TEXTURE"

## Return Type Values:
| Value | Name |
| --- | --- |
| 0 | Succeeded |
| 1 | In Progress |
| 2 | Failed |

