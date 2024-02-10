---
ns: ENTITY
aliases: ["0x6b9bbd38ab0796df"]
---
## ATTACH_ENTITY_TO_ENTITY

```c
// 0x6B9BBD38AB0796DF
void ATTACH_ENTITY_TO_ENTITY(Entity entity, int SecondEntityBoneIndex, Vector3 vecOffset, Vector3 vecRotation, bool DetachWhenDead, bool DetachWhenRagdoll, bool ActiveCollisions, bool UseBasicAttachIfPed, int RotOrder, bool AttachOffsetIsRelative, bool MarkAsNoLongerNeededWhenDetached);
```

Attaches an entity to another entity with a non physical attachement.

## RotOrder Values:
| Value | Name |
| --- | --- |
| 0 | Xyz |
| 1 | Xzy |
| 2 | Yxz |
| 3 | Yzx |
| 4 | Zxy |
| 5 | Zyx |
| 6 | Max |


None physical attachment - collision is turned off for entity.


## Parameters
* **entity**: 
* **SecondEntityBoneIndex**: use 0 for the skeleton root or -1 for entity matrix. Can attach to any bone on the
* **vecOffset**: is from the root of the bone you're attaching to (the entity's position if bone=0)
* **vecRotation**: is used to build a rotation matrix, relative to the bone you're attaching too (the entity itself if bone=0)
* **DetachWhenDead**: detaches the ped when he dies (this is only used by peds)
* **DetachWhenRagdoll**: detaches the ped when he ragdolls (this is only used by peds)
* **ActiveCollisions**: leave the collisions activated on the attached object
* **UseBasicAttachIfPed**: This forces a path, even for peds, that will use all three rotation components
* **RotOrder**: 
* **AttachOffsetIsRelative**: 
* **MarkAsNoLongerNeededWhenDetached**: 
