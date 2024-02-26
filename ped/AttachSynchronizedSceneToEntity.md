---
ns: PED
aliases: ["0x272e4723b56a3b96"]
---
## ATTACH_SYNCHRONIZED_SCENE_TO_ENTITY

```c
// 0x272E4723B56A3B96
void ATTACH_SYNCHRONIZED_SCENE_TO_ENTITY(Entity entity, int bone);
```

Attaches a synced scene to an entity.

Use this command to attach a synchronized scene to an entity. Once attached, the root of the scene will follow the ped until [DETACH_SYNCHRONIZED_SCENE](#_0x6D38F1F04CBB37EA) is called. When attached, the scene's origin becomes an offset from the parent object.


## Parameters
* **entity**: 
* **bone**: The bone index on the entity to attach
