---
ns: TASK
aliases: ["0x6a071245eb0d1882"]
---
## TASK_GO_TO_ENTITY

```c
// 0x6A071245EB0D1882
void TASK_GO_TO_ENTITY(Ped ped, Entity entity, int Time, float SeekRadius, float MoveBlendRatio, float SlowDownDistance, int GotoFlags);
```

Tells a ped to go to another entity.

## Values for `GotoFlags`:
| Value | Name |
| --- | --- |
| 0 | Default |
| 1 | Never Slow For Path Length |


if Time is chosen to be -1 the ped will never warp.


## Parameters
* **ped**: 
* **entity**: 
* **Time**: (Default value: `Default_Time_Before_Warp`)
* **SeekRadius**: (Default value: `Default_Seek_Radius`)
* **MoveBlendRatio**: (Default value: `Pedmoveblendratio_Run`)
* **SlowDownDistance**: (Default value: `2`)
* **GotoFlags**: (Default value: `Default`)
