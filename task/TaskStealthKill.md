---
ns: TASK
aliases: ["0xaa5dc05579d60bd9"]
---
## TASK_STEALTH_KILL

```c
// 0xAA5DC05579D60BD9
void TASK_STEALTH_KILL(Ped ped, Ped ped, int StealthKillActionResultId, float fDesiredMoveBlendRatio, int iFlags);
```

Gives designated ped a stealth task which will navigate to a defined target ped and perform a stealth kill

## iFlags Values:
| Value | Name |
| --- | --- |
| 0 | Default |
| 1 | Force Stealth Mode |


## Parameters
* **ped**: 
* **ped**: 
* **StealthKillActionResultId**: Hash of the CActionResult defined in action_table.meta
* **fDesiredMoveBlendRatio**: (Default value: `Pedmoveblendratio_Walk`)
* **iFlags**: (Default value: `Default`)
