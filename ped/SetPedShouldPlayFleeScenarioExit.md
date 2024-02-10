---
ns: PED
aliases: ["0xeeed8fafec331a70"]
---
## SET_PED_SHOULD_PLAY_FLEE_SCENARIO_EXIT

```c
// 0xEEED8FAFEC331A70
bool SET_PED_SHOULD_PLAY_FLEE_SCENARIO_EXIT(Ped ped, Vector3 vDangerPosition);
```

Control how the ped leaves their scenario when they get their next task.

When this ped receives its next script task, they will do a flee exit from the scenario point. It will take a few frames for the exit to be completed. Unlike the other force exit commands, the ped must be using the scenario task before this is called. Returns true if the position was successfully set.


## Parameters
* **ped**: 
* **vDangerPosition**: a position that the ped will play their exit towards.
