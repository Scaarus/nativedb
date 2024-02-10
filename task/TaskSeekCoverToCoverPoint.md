---
ns: TASK
aliases: ["0xd43d95c7a869447f"]
---
## TASK_SEEK_COVER_TO_COVER_POINT

```c
// 0xD43D95C7A869447F
void TASK_SEEK_COVER_TO_COVER_POINT(Coverpoint coverpoint, Vector3 FromPosition, int Time, bool CanPeekAndAim);
```

```
Task making the ped seek cover at the scripted cover point specified in CoverIndex.

Seeks cover in such a way as to avoid fire from position fromX, fromY, fromZ. Once cover is reached the ped will hide behind it for Time milliseconds then the task will end, if Time is zero the ped will hide behind it indefinitely and the task will never end.
```
