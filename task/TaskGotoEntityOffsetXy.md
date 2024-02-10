---
ns: TASK
aliases: ["0x338e7ef52b6095a9"]
---
## TASK_GOTO_ENTITY_OFFSET_XY

```c
// 0x338E7EF52B6095A9
void TASK_GOTO_ENTITY_OFFSET_XY(Entity entity, int Time, float fTargetRadius, float fXOffset, float fYOffset, float MoveBlendRatio, int OffsetFlags);
```

Tells the ped to go to an offset from the target entity. A combination of flags from the ESEEK_ENTITY_OFFSET_FLAGS enum may be passed in.

## OffsetFlags Values:
| Value | Name |
| --- | --- |
| 0 | Default |
| 1 | Offset Orientates With Entity |
| 2 | Keep To Pavements |


The destination point is (fXOffset,fYOffset) from the other entity’s position. Query for this task using 'SCRIPT_TASK_GOTO_ENTITY_OFFSET' as for TASK_GO_TO_ENTITY

if Time is chosen to be -1 the ped will never warp.

