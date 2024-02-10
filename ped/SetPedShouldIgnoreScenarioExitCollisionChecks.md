---
ns: PED
aliases: ["0x425aecf167663f48"]
---
## SET_PED_SHOULD_IGNORE_SCENARIO_EXIT_COLLISION_CHECKS

```c
// 0x425AECF167663F48
void SET_PED_SHOULD_IGNORE_SCENARIO_EXIT_COLLISION_CHECKS(Ped ped, bool IgnoreChecks);
```

Control how the ped checks against world geometry when exiting scenarios.

When this ped needs to leave their scenario, set if they test for collision against the world when they leave. This will prevent them from getting stuck in their point because there was nearby collision. Use with care! This command will also ignore the navmesh checks.

