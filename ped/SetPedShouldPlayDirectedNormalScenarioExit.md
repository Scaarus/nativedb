---
ns: PED
aliases: ["0xec6935ebe0847b90"]
---
## SET_PED_SHOULD_PLAY_DIRECTED_NORMAL_SCENARIO_EXIT

```c
// 0xEC6935EBE0847B90
bool SET_PED_SHOULD_PLAY_DIRECTED_NORMAL_SCENARIO_EXIT(Ped ped, Vector3 vReactPosition);
```

```
Control how the ped leaves their scenario when they get their next task.

When this ped receives its next script task, they will exit from their scenario using the normal scenario exit. Exiting the scenario may take several frames while the ped is playing the exit animation. Returns true if the position was successfully set. If the ped is not currently using a scenario at the time of the command or 0,0,0 is specified as the reaction position, then the ped will by default attempt to direct their exit forwards.
```

## Parameters
* **ped**: 
* **vReactPosition**: a position towards which the scenario ped should direct their exit.
