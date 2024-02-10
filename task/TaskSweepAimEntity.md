---
ns: TASK
aliases: ["0x2047c02158d6405a"]
---
## TASK_SWEEP_AIM_ENTITY

```c
// 0x2047C02158D6405A
void TASK_SWEEP_AIM_ENTITY(Ped ped, string pAnimDictName, string pLowAnimName, string pMedAnimName, string pHiAnimName, int runTime, Entity entity, float turnRate, float BlendInDuration);
```

```
Set the desired ped to point (anims dependant) at the desired entity. Turn rate is default to PI * 0.5f, increasing will turn faster.
```
