---
ns: TASK
aliases: ["0xc22b40579a498ca4"]
---
## TASK_SUBMARINE_GOTO_AND_STOP

```c
// 0xC22B40579A498CA4
void TASK_SUBMARINE_GOTO_AND_STOP(Ped ped, Vehicle vehicle, Vector3 TargetCoords, bool AutoPilot);
```

To get submarines to stop at a position when the player gets out

bAutoPilot will apply the task directly to the vehicle, and apply some flags to allow this task to run with no driver

Tells a submarine to goto and stop at the position given

