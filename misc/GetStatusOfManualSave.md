---
ns: MISC
aliases: ["0x397baa01068baa96"]
---
## GET_STATUS_OF_MANUAL_SAVE

```c
// 0x397BAA01068BAA96
savegame_operation_status GET_STATUS_OF_MANUAL_SAVE();
```

```
Returns the status of the manual save that is launched by SET_SAVE_MENU_ACTIVE()

Possible return values:
| Index | Name |
| --- | --- |
| 66 | Succeeded |
| 67 | In Progress |
| 68 | Failed |
```
