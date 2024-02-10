---
ns: PED
aliases: ["0xa3a9299c4f2adb98"]
---
## SET_PED_SHOULD_PLAY_NORMAL_SCENARIO_EXIT

```c
// 0xA3A9299C4F2ADB98
void SET_PED_SHOULD_PLAY_NORMAL_SCENARIO_EXIT(Ped ped);
```

Control how the ped leaves their scenario when they get their next task.

When this ped receives its next script task, they will exit from their scenario using the normal scenario exit. Exiting the scenario may take several frames while the ped is playing the exit animation.

