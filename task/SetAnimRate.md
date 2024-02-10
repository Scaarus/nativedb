---
ns: TASK
aliases: ["0x032d49c5e359c847"]
---
## SET_ANIM_RATE

```c
// 0x032D49C5E359C847
void SET_ANIM_RATE(Entity entity, float rate, int priority, bool secondary);
```

Sets the rate of a clip on a scripted anim task.

## priority Values:
| Value | Name |
| --- | --- |
| 0 | Low |
| 1 | Medium |
| 2 | High |


Sets the current rate of the clips on a priority level on the scripted anim task,


## Parameters
* **entity**: 
* **rate**: 
* **priority**: The priority level to apply the filter to. AF_PRIORITY_LOW, AF_PRIORITY_MEDIUM or AF_PRIORITY_HIGH.
* **secondary**: 
