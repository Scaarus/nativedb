---
ns: TASK
aliases: ["0x207f1a47c0342f48"]
---
## SET_ANIM_WEIGHT

```c
// 0x207F1A47C0342F48
void SET_ANIM_WEIGHT(Entity entity, float blendWeight, int priority, int index, bool secondary);
```

Sets the blend weight of a clip playing on a scripted anim task.

## priority Values:
| Value | Name |
| --- | --- |
| 0 | Low |
| 1 | Medium |
| 2 | High |


Sets the blend weight of a clip playing on the scripted anim task,


## Parameters
* **entity**: 
* **blendWeight**: 
* **priority**: The priority level the clip is playing on. AF_PRIORITY_LOW, AF_PRIORITY_MEDIUM or AF_PRIORITY_HIGH.
* **index**: The index of the clip to set on the given priority (used when the priority level is playing a blend of clips, when playing a single clip this can be left blank).
* **secondary**: 
