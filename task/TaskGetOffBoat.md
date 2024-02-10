---
ns: TASK
aliases: ["0x9c00e77af14b2dff"]
---
## TASK_GET_OFF_BOAT

```c
// 0x9C00E77AF14B2DFF
void TASK_GET_OFF_BOAT(int iTimer);
```

Tells a ped to get off a boat.

There is no need to specify a boat, as the task itself will figure out which boat is underneath the ped. This task does a number of linetests and is thus pretty expensive, so use with care (ie. not repeatedly!) NOTE: This task is automatically given to group peds, if they are on a boat but their leader is not.

