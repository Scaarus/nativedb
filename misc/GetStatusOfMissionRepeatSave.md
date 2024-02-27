---
ns: MISC
aliases: ["0x2b5e102e4a42f2bf"]
---
## GET_STATUS_OF_MISSION_REPEAT_SAVE

```c
// 0x2B5E102E4A42F2BF
int GET_STATUS_OF_MISSION_REPEAT_SAVE();
```

Check the status of the save triggered by [`QUEUE_MISSION_REPEAT_SAVE`](#_0x44A0BDC559B35F6E)() or [`QUEUE_MISSION_REPEAT_SAVE_FOR_BENCHMARK_TEST`](#_0xEB2104E905C6F2E9)()

## Return Type Values:
| Value | Name |
| --- | --- |
| 0 | Succeeded |
| 1 | In Progress |
| 2 | Failed |

