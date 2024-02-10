---
ns: GRAPHICS
aliases: ["0x90a78ecaa4e78453"]
---
## GET_STATUS_OF_TAKE_MISSION_CREATOR_PHOTO

```c
// 0x90A78ECAA4E78453
photo_operation_status GET_STATUS_OF_TAKE_MISSION_CREATOR_PHOTO();
```

```
Call this after calling BEGIN_TAKE_MISSION_CREATOR_PHOTO to check when the operation has finished, and whether it succeeded.

Possible return values:
| Index | Name |
| --- | --- |
| 19 | Succeeded |
| 20 | In Progress |
| 21 | Failed |
```
