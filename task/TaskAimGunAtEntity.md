---
ns: TASK
aliases: ["0x9b53bb6e8943af53"]
---
## TASK_AIM_GUN_AT_ENTITY

```c
// 0x9B53BB6E8943AF53
void TASK_AIM_GUN_AT_ENTITY(Entity entity, int Duration, bool InstantBlendToAim);
```

Tells a ped to aim a gun a an entity.

Duration is measured in milliseconds. InstantBlendToAim will skip the idle transition and instantly blend to the aim pose

The first ped must have a gun and it must be his current weapon to use this command.

