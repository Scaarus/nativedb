---
ns: PED
aliases: ["0xb3b1cb349ff9c75d"]
---
## SET_CAN_ATTACK_FRIENDLY

```c
// 0xB3B1CB349FF9C75D
void SET_CAN_ATTACK_FRIENDLY(Ped ped, bool Enable, bool ChangeTargettingLockOnState);
```

Allow peds to attack friendlies

If bChangeTargettingLockOnState is true it will set whether target lock onto friendlies is also changed by bEnable. This target lock onto friendlies state is cleared at mission clean up.

