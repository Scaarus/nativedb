---
ns: GRAPHICS
aliases: ["0x90a78ecaa4e78453"]
---
## GET_STATUS_OF_TAKE_MISSION_CREATOR_PHOTO

```c
// 0x90A78ECAA4E78453
int GET_STATUS_OF_TAKE_MISSION_CREATOR_PHOTO();
```

Call this after calling [`BEGIN_TAKE_MISSION_CREATOR_PHOTO`](#_0x1DD2139A9A20DCE8) to check when the operation has finished, and whether it succeeded.

## Return Type Values:
| Value | Name |
| --- | --- |
| 0 | Succeeded |
| 1 | In Progress |
| 2 | Failed |

