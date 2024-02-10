---
ns: ENTITY
aliases: ["0x40fdedb72f8293b2"]
---
## FORCE_ENTITY_AI_AND_ANIMATION_UPDATE

```c
// 0x40FDEDB72F8293B2
void FORCE_ENTITY_AI_AND_ANIMATION_UPDATE(Entity entity);
```

```
Forces the entities ai and animation to be processed again this frame. This command is expensive and must be used sparingly! Its primary purpose is to update entity animations immediately on the first frame of a scripted cut scene (where a camera cut is being used).
```
