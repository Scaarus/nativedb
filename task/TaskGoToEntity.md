---
ns: TASK
aliases: ["0x6a071245eb0d1882"]
---
## TASK_GO_TO_ENTITY

```c
// 0x6A071245EB0D1882
void TASK_GO_TO_ENTITY(Ped ped, Entity entity, int Time, float SeekRadius, float MoveBlendRatio, float SlowDownDistance, int GotoFlags);
```

```
Tells a ped to go to another entity.

Possible values for GotoFlags:
| Index | Name |
| --- | --- |
| 0 | Default |
| 1 | Never Slow For Path Length |


if Time is chosen to be -1 the ped will never warp.
```
