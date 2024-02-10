---
ns: TASK
aliases: ["0x126ef75f1e17abe5"]
---
## TASK_SCRIPTED_ANIMATION

```c
// 0x126EF75F1E17ABE5
void TASK_SCRIPTED_ANIMATION(Ped ped, anim_data priorityLow, anim_data priorityMid, anim_data priorityHigh, float fTaskBlendInDuration, float fTaskBlendOutDuration);
```

Starts a task that will play back on or more anims.

priorityLow, priorityMid and

Plays one or more anims on the specified ped


## Parameters
* **ped**: 
* **priorityLow**: 
* **priorityMid**: 
* **priorityHigh**: Structures detailing the anim (or combination of anims) to play back on the low, medium and high priority slots within the anim task. Anims on different slots can be blended in and out independently of each other, and can use different filters and flags to affect thier behaviour (see the definitions of ANIM_DATA and ANIMATION_FLAGS for more information). It is also possible to play a blend of up to 3 anims at a time at each priority, with control over the anims phases, rates, and weight relative to one another.
* **fTaskBlendInDuration**: the time over which the task will blend in (in seconds)
* **fTaskBlendOutDuration**: the time over which the task will blend out (in seconds)
