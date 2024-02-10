---
ns: ENTITY
aliases: ["0x5c48b75732c8456c"]
---
## ATTACH_ENTITY_BONE_TO_ENTITY_BONE

```c
// 0x5C48B75732C8456C
void ATTACH_ENTITY_BONE_TO_ENTITY_BONE(Entity entity, int FirstEntityBoneIndex, int SecondEntityBoneIndex, bool DoInitialWarp, bool CollideWithEntity);
```

```
Attaches an entity to another entity using a none physical attachment.

None physical attachment - collision is turned off for entity.
```

## Parameters
* **entity**: 
* **FirstEntityBoneIndex**: refers to the bone on the first entity which is being attached.
* **SecondEntityBoneIndex**: refers to the bone on the second entity that you're attaching the first entity to.
* **DoInitialWarp**: ** NOT USED FOR PEDS** specifies whether to warp the object to the specified attach point. If not, then the initial seperation will be used as an allowed give in the attachment (e.g. a rope length)
* **CollideWithEntity**: ** ONLY USED FOR PEDS** of set the two entities will collide with each other once attached
