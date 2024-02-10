---
ns: GRAPHICS
aliases: ["0x1670f8d05056f257"]
---
## GET_STATUS_OF_LOAD_MISSION_CREATOR_PHOTO

```c
// 0x1670F8D05056F257
photo_operation_status GET_STATUS_OF_LOAD_MISSION_CREATOR_PHOTO(string szContentID);
```

Returns the status of the last photo load to have been successfully started by LOAD_MISSION_CREATOR_PHOTO

## Return Type Values:
| Value | Name |
| --- | --- |
| 19 | Succeeded |
| 20 | In Progress |
| 21 | Failed |

