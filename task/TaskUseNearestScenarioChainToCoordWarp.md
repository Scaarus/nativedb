---
ns: TASK
aliases: ["0x97a28e63f0ba5631"]
---
## TASK_USE_NEAREST_SCENARIO_CHAIN_TO_COORD_WARP

```c
// 0x97A28E63F0BA5631
void TASK_USE_NEAREST_SCENARIO_CHAIN_TO_COORD_WARP(Vector3 vPosition, float fRange, int iTimeToLeaveMS);
```

Warps the ped into the cloeset scenario to the pos, with support for chaining to linked points (wraps CTaskUseScenario in CTaskUnalerted).

Make sure the scenario point or objects its attached to is loaded at the time.


## Parameters
* **vPosition**: 
* **fRange**: 
* **iTimeToLeaveMS**: (Default value: `0`)
