---
ns: PED
aliases: ["0x5b6010b3cbc29095"]
---
## SET_PED_SHOULD_IGNORE_SCENARIO_NAV_CHECKS

```c
// 0x5B6010B3CBC29095
void SET_PED_SHOULD_IGNORE_SCENARIO_NAV_CHECKS(Ped ped, bool IgnoreChecks);
```

```
Control how the ped checks for a valid path when exiting scenarios.

When this ped needs to leave their scenario, set if they should test for valid navmesh when they leave. This will prevent them from getting stuck in their point. Use with care!
```
