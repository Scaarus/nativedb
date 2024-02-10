---
ns: TASK
aliases: ["0xf166e48407bac484"]
---
## TASK_COMBAT_PED

```c
// 0xF166E48407BAC484
void TASK_COMBAT_PED(Ped ped, int CombatFlags, int TaskThreatResponseFlags);
```

Tells a ped to combat another ped.

## CombatFlags Values:
| Value | Name |
| --- | --- |
| 0 | None |
| 67108864 | Prevent Changing Target |
| 134217728 | Disable Aim Intro |


## TaskThreatResponseFlags Values:
| Value | Name |
| --- | --- |
| 0 | None |
| 16 | Can Fight Armed Peds When Not Armed |
