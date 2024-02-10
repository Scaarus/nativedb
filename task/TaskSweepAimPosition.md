---
ns: TASK
aliases: ["0x7afe8fdc10bc07d2"]
---
## TASK_SWEEP_AIM_POSITION

```c
// 0x7AFE8FDC10BC07D2
void TASK_SWEEP_AIM_POSITION(Ped ped, string pAnimDictName, string pLowAnimName, string pMedAnimName, string pHiAnimName, int runTime, Vector3 scrVecPosition, float turnRate, float BlendInDuration);
```

```
Set the desired ped to point (anims dependant) at the desired position. Turn rate is default to PI * 0.5f, increasing will turn faster.
```
