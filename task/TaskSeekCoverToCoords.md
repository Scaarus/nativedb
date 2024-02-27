---
ns: TASK
aliases: ["0x39246a6958ef072c"]
---
## TASK_SEEK_COVER_TO_COORDS

```c
// 0x39246A6958EF072C
void TASK_SEEK_COVER_TO_COORDS(Vector3 CooverPosition, Vector3 FromPosition, int Time, bool CanPeekAndAim);
```

Tells a ped to seek cover to given coords VecCooverCoors in such a way as to hide from VecFromCoors.

The ped will find the nearest cover point to the coords given. Once cover is reached the ped will hide behind it for Time milliseconds then the task will end, if Time is zero the ped will hide behind it indefinitely and the task will never end.


## Parameters
* **CooverPosition**: 
* **FromPosition**: 
* **Time**: 
* **CanPeekAndAim**: (Default value: `False`)
