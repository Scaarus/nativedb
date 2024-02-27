---
ns: TASK
aliases: ["0x00a9010cfe1e3533"]
---
## GET_SEQUENCE_PROGRESS

```c
// 0x00A9010CFE1E3533
int GET_SEQUENCE_PROGRESS();
```

Gets the progress of a sequence of tasks.
ReturnProgress is an INT and will be -1 before the sequence task begins. Once the sequence has begun, ReturnProgress will be given a value reflecting which task in the sequence is being performed (0 = the first task).

Before calling this command, you should call [`GET_SCRIPT_TASK_STATUS`](#_0x77F1BEB8863288D5) to make sure that SCRIPT_TASK_PERFORM_SEQUENCE is running.

