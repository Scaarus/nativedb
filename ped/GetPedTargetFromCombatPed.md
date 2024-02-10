---
ns: PED
aliases: ["0x32c27a11307b01cc"]
---
## GET_PED_TARGET_FROM_COMBAT_PED

```c
// 0x32C27A11307B01CC
Entity GET_PED_TARGET_FROM_COMBAT_PED(Ped ped, bool ForceLoSCheck);
```

```
Return the index of the target ped with which the ped is in combat with. Allow for an optional LoS check to be enforced. Will return 0 if there is no target ped or if the ped is not in TASK_COMBAT
```
