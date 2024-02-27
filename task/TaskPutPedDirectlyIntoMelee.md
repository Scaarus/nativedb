---
ns: TASK
aliases: ["0x1c6cd14a876ffe39"]
---
## TASK_PUT_PED_DIRECTLY_INTO_MELEE

```c
// 0x1C6CD14A876FFE39
void TASK_PUT_PED_DIRECTLY_INTO_MELEE(Ped ped, float BlendInDuration, float nTimeInTask, float StrafePhaseSync, int AiCombatFlags);
```

Puts the ped directly into melee

## AiCombatFlags Values:
| Value | Name |
| --- | --- |
| 0 | None |
| 67108864 | Prevent Changing Target |
| 134217728 | Disable Aim Intro |


## Parameters
* **ped**: 
* **BlendInDuration**: 
* **nTimeInTask**: 
* **StrafePhaseSync**: 
* **AiCombatFlags**: only applies when the ped being given the task is an AI ped (Default value: `None`)
