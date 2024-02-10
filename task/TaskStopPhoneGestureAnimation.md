---
ns: TASK
aliases: ["0x3fa00d4f4641bfae"]
---
## TASK_STOP_PHONE_GESTURE_ANIMATION

```c
// 0x3FA00D4F4641BFAE
void TASK_STOP_PHONE_GESTURE_ANIMATION(Ped ped, float fBlendOutOverride);
```

Stops a player phone animation


## Parameters
* **ped**: 
* **fBlendOutOverride**: Overrides the blend out time set in TASK_PLAY_PHONE_GESTURE_ANIMATION. Will use the originally set blend out time if left at -1.0.
