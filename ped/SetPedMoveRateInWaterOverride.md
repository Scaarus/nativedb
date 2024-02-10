---
ns: PED
aliases: ["0x0b3e35ac043707d9"]
---
## SET_PED_MOVE_RATE_IN_WATER_OVERRIDE

```c
// 0x0B3E35AC043707D9
void SET_PED_MOVE_RATE_IN_WATER_OVERRIDE(Ped ped, float DesiredRate);
```

Set the desired move speed override of swimming/diving - needs to be called everyframe, or will revert 1.0f

MaxDesiredRate = 3.0 (anything above this just looks completely ridiculous)

