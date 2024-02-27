---
ns: ENTITY
aliases: ["0xfd1695c5d3b05439"]
---
## ATTACH_ENTITY_BONE_TO_ENTITY_BONE_Y_FORWARD

```c
// 0xFD1695C5D3B05439
void ATTACH_ENTITY_BONE_TO_ENTITY_BONE_Y_FORWARD(Entity entity, int FirstEntityBoneIndex, int SecondEntityBoneIndex, bool DoInitialWarp, bool CollideWithEntity);
```

Attaches an entity to another entity using a none physical attachment.

Same as the above function but assumes that the bone is facing along the y axis


## Parameters
* **entity**: 
* **FirstEntityBoneIndex**: refers to the bone on the first entity which is being attached.
* **SecondEntityBoneIndex**: refers to the bone on the second entity that you're attaching the first entity to.
* **DoInitialWarp**: ** NOT USED FOR PEDS** specifies whether to warp the object to the specified attach point. If not, then the initial seperation will be used as an allowed give in the attachment (e.g. a rope length) (Default value: `True`)
* **CollideWithEntity**: ** ONLY USED FOR PEDS** of set the two entities will collide with each other once attached (Default value: `False`)
