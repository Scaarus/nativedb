---
ns: TASK
aliases: ["0x77f1beb8863288d5"]
---
## GET_SCRIPT_TASK_STATUS

```c
// 0x77F1BEB8863288D5
int GET_SCRIPT_TASK_STATUS(Any* TaskName);
```

Gets the current status of a scrioted task.

## Return Type Values:
| Value | Name |
| --- | --- |
| 0 | WAITING_TO_START_TASK |
| 1 | PERFORMING_TASK |
| 2 | DORMANT_TASK |
| 3 | VACANT_STAGE |
| 4 | GROUP_TASK_STAGE |
| 5 | ATTRACTOR_SCRIPT_TASK_STAGE |
| 6 | SECONDARY_TASK_STAGE |
| 7 | FINISHED_TASK |

TaskName should be the name of the task command, taken from the header file: Commands_task.sch If TaskName is chosen to be NULL the command will search for any scripted task that is being processed, rather than a specific task. ReturnStatusOut should be declared as a SCRIPTTASKSTATUS. ReturnStatusOut will be one of the entries in the header file: X:\GTA\gta_rage_scripts\include\commands_task.sch If you're trying to get the status of a task that is performed as part of a sequence then it will never return as True because the character in question is told to [`TASK_PERFORM_SEQUENCE`](#_0x5ABA3986D90D8A3B). So, check for GET_SCRIPT_TASK_STATUS ( CharID, SCRIPT_TASK_PERFORM_SEQUENCE, ReturnStatus) instead. Alternatively, you can check to see if a character is performing a sequence then use [`GET_SEQUENCE_PROGRESS`](#_0x00A9010CFE1E3533) to find out which specific task within the sequence your character is performing.

