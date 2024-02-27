---
ns: TASK
aliases: ["0xddf3cb5a0a4c0b49"]
---
## SET_ANIM_PHASE

```c
// 0xDDF3CB5A0A4C0B49
void SET_ANIM_PHASE(Entity entity, float phase, int priority, bool secondary);
```

Sets the phase of a clip on a scripted anim task.

## Values for `priority`:
| Value | Name |
| --- | --- |
| 0 | Low |
| 1 | Medium |
| 2 | High |


Sets the current phase of the clips on a priority level on the scripted anim task,


## Parameters
* **entity**: 
* **phase**: The new phase of the clip(s)
* **priority**: The priority level to apply the filter to. AF_PRIORITY_LOW, AF_PRIORITY_MEDIUM or AF_PRIORITY_HIGH. (Default value: `Low`)
* **secondary**: (Default value: `False`)
