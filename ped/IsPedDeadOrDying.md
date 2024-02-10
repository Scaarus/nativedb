---
ns: PED
aliases: ["0x3317dedb88c95038"]
---
## IS_PED_DEAD_OR_DYING

```c
// 0x3317DEDB88C95038
bool IS_PED_DEAD_OR_DYING(Ped ped, bool CheckMeleeDeathFlags);
```

Checks that the ped is running CTaskDamageDeath

CheckMeleeDeathFlags, if TRUE IS_PED_DEAD_OR_DYING will return TRUE In the case of doing a paired takedown move before they are running the dead task

Cannot give ped tasks if dead or dying. I.e. if the ped is running CTaskDamageDeath. Calling IS_PED_FATALLY_INJURED doesn't necessarily mean that CTaskDamageDeath has started yet

