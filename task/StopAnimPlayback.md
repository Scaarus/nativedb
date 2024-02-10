---
ns: TASK
aliases: ["0xee08c992d238c5d1"]
---
## STOP_ANIM_PLAYBACK

```c
// 0xEE08C992D238C5D1
void STOP_ANIM_PLAYBACK(Entity entity, int priority, bool secondary);
```

Stops animation on an existing TASK_SCRIPTED_ANIMATION.

## priority Values:
| Value | Name |
| --- | --- |
| 0 | Low |
| 1 | Medium |
| 2 | High |


Stops playback of animation on the given priority level of an existing TASK_SCRIPTED_ANIMATION


## Parameters
* **entity**: 
* **priority**: The priority level to stop. specify either AF_PRIORITY_HIGH, AF_PRIORITY_MEDIUM or AF_PRIORITY_LOW. Any animation playing at this priority level will blend out with its specified blend out duration.
* **secondary**: 
