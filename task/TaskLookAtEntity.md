---
ns: TASK
aliases: ["0x69f4be8c8cc4796c"]
---
## TASK_LOOK_AT_ENTITY

```c
// 0x69F4BE8C8CC4796C
void TASK_LOOK_AT_ENTITY(Ped ped, Entity entity, int time, int priority);
```

Tells a ped to look at an entity.

## priority Values:
| Value | Name |
| --- | --- |
| 0 | Very Low |
| 265 | Low |
| 266 | Medium |
| 267 | High |
| 268 | Very High |


If LookTime is -1 the ped will perform the task forever. The optional flags parameter is made by combining any of the following flags from commands_task.sch.

