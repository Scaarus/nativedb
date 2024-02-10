---
ns: PED
aliases: ["0x9a77dfd295e29b09"]
---
## TOGGLE_SCENARIO_PED_COWER_IN_PLACE

```c
// 0x9A77DFD295E29B09
void TOGGLE_SCENARIO_PED_COWER_IN_PLACE(Ped ped, bool Start);
```

Forces the given scenario ped to start or stop cowering in place.

bStart of true means to start cowering, bStart of false means to stop cowering. The ped will also stop cowering if they receive a script command.

