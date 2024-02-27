---
ns: TASK
aliases: ["0xe39b4ff4fdebde27"]
---
## TASK_GOTO_ENTITY_OFFSET

```c
// 0xE39B4FF4FDEBDE27
void TASK_GOTO_ENTITY_OFFSET(Entity entity, int Time, float SeekRadius, float SeekAngle, float MoveBlendRatio, int OffsetFlags);
```

Tells the ped to go to an offset from the target entity. A combination of flags from the ESEEK_ENTITY_OFFSET_FLAGS enum may be passed in.

## Values for `OffsetFlags`:
| Value | Name |
| --- | --- |
| 0 | Default |
| 1 | Offset Orientates With Entity |
| 2 | Keep To Pavements |


The destination point is SeekRadiusFloat metres from the other entity’s position. The exact destination position is calculated using the other entity’s heading offset by SeekAngleFloat degree

if Time is chosen to be -1 the ped will never warp.


## Parameters
* **entity**: 
* **Time**: (Default value: `Default_Time_Before_Warp`)
* **SeekRadius**: (Default value: `Default_Seek_Radius`)
* **SeekAngle**: (Default value: `0`)
* **MoveBlendRatio**: (Default value: `Pedmoveblendratio_Run`)
* **OffsetFlags**: (Default value: `Default`)
