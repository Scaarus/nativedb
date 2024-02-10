---
ns: MISC
aliases: ["0x2b5e102e4a42f2bf"]
---
## GET_STATUS_OF_MISSION_REPEAT_SAVE

```c
// 0x2B5E102E4A42F2BF
savegame_operation_status GET_STATUS_OF_MISSION_REPEAT_SAVE();
```

Check the status of the save triggered by QUEUE_MISSION_REPEAT_SAVE() or QUEUE_MISSION_REPEAT_SAVE_FOR_BENCHMARK_TEST()

## Return Type Values:
| Value | Name |
| --- | --- |
| 66 | Succeeded |
| 67 | In Progress |
| 68 | Failed |

