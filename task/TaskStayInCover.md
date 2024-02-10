---
ns: TASK
aliases: ["0xe5da8615a6180789"]
---
## TASK_STAY_IN_COVER

```c
// 0xE5DA8615A6180789
void TASK_STAY_IN_COVER(Ped ped);
```

This task will cause the ped to continuously look for cover within their defensive area, the defensive area can be moved and the ped will move to within the new area. If the defensive area has a direction the ped will always seek cover from that direction.

This can only be called on a ped which has a valid defensive area.

