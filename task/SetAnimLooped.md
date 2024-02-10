---
ns: TASK
aliases: ["0x70033c3cc29a1ff4"]
---
## SET_ANIM_LOOPED

```c
// 0x70033C3CC29A1FF4
void SET_ANIM_LOOPED(Entity entity, bool looped, int priority, bool secondary);
```

Sets whether clips on a scripted anim task should loop.

## priority Values:
| Value | Name |
| --- | --- |
| 0 | Low |
| 1 | Medium |
| 2 | High |


Sets wether the clips on a priority level on the scripted anim task should loop,


## Parameters
* **entity**: 
* **looped**: 
* **priority**: The priority level to apply the filter to. AF_PRIORITY_LOW, AF_PRIORITY_MEDIUM or AF_PRIORITY_HIGH.
* **secondary**: 
