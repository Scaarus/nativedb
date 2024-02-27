---
ns: TASK
aliases: ["0x75ac2b60386d89f2"]
---
## TASK_SEEK_COVER_FROM_POS

```c
// 0x75AC2B60386D89F2
void TASK_SEEK_COVER_FROM_POS(Vector3 FromPosition, int Time, bool CanPeekAndAim);
```

The ped will seek cover from the given coordinates.

If after a search no cover point can be found the task will finish. Once cover is reached the ped will hide behind it for Time milliseconds then the task will end, if Time is zero the ped will hide behind it indefinitely and the task will never end.


## Parameters
* **FromPosition**: 
* **Time**: 
* **CanPeekAndAim**: (Default value: `False`)
