---
ns: TASK
aliases: ["0x8fbb6758b3b3e9ec"]
---
## TASK_PLAY_PHONE_GESTURE_ANIMATION

```c
// 0x8FBB6758B3B3E9EC
void TASK_PLAY_PHONE_GESTURE_ANIMATION(Ped ped, string pAnimDictName, string pAnimName, string pFilterName, float fTaskBlendInDuration, float fTaskBlendOutDuration, bool IsLooping, bool HoldLastFrame);
```

Plays a gesture animation whilst using phone


## Parameters
* **ped**: 
* **pAnimDictName**: 
* **pAnimName**: 
* **pFilterName**: 
* **fTaskBlendInDuration**: the time over which the task will blend in (in seconds)
* **fTaskBlendOutDuration**: the time over which the task will blend out (in seconds)
* **IsLooping**: Specifies whether to loop animation or not
* **HoldLastFrame**: If true, holds final position of animation, else returns to starting position. Call TASK_STOP_PHONE_GESTURE_ANIMATION to return to original position if true.
