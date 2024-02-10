---
ns: TASK
aliases: ["0x84d32b3bec531324"]
---
## TASK_SEEK_COVER_FROM_PED

```c
// 0x84D32B3BEC531324
void TASK_SEEK_COVER_FROM_PED(Ped ped, int Time, bool CanPeekAndAim);
```

```
The ped will seek cover from the given peds location.

Once cover is reached the ped will hide behind it for Time milliseconds then the task will end, if Time is zero the ped will hide behind it indefinitely and the task will never end.
```
