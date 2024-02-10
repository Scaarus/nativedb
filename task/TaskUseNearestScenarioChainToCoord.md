---
ns: TASK
aliases: ["0x9fda1b3d7e7028b3"]
---
## TASK_USE_NEAREST_SCENARIO_CHAIN_TO_COORD

```c
// 0x9FDA1B3D7E7028B3
void TASK_USE_NEAREST_SCENARIO_CHAIN_TO_COORD(Vector3 vPosition, float fRange, int iTimeToLeaveMS);
```

```
Puts the ped into the cloeset scenario to the coord, with support for chaining to linked points (wraps CTaskUseScenario in CTaskUnalerted).

Make sure the scenario point or objects its attached to is loaded at the time.
```
