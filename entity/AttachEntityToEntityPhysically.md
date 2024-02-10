---
ns: ENTITY
aliases: ["0xc3675780c92f90f9"]
---
## ATTACH_ENTITY_TO_ENTITY_PHYSICALLY

```c
// 0xC3675780C92F90F9
void ATTACH_ENTITY_TO_ENTITY_PHYSICALLY(Entity entity, int FirstEntityBoneIndex, int SecondEntityBoneIndex, Vector3 SecondEntityOffset, Vector3 FirstEntityOffset, Vector3 vecRotation, float PhysicalStrength, bool ConstrainRotation, bool DoInitialWarp, bool CollideWithEntity, bool AddInitialSeperation, int RotOrder);
```

Attaches an entity to another entity using a physical attachment.

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


Physical attachment using rage constraints - entities are still physically active in the world.


## Parameters
* **entity**: 
* **FirstEntityBoneIndex**: refers to the bone on the first entity which is being attached.
* **SecondEntityBoneIndex**: refers to the bone on the second entity that you're attaching the first entity to. This lets us attach for example, a ped's hand (ragdoll) to a car door. Some objects are fragment objects, and have a skeleton with multiple pieces that break apart, and this may be useful for them.
* **SecondEntityOffset**: the offset from the root of the bone on the the first entity.
* **FirstEntityOffset**: the offset from the root of the bone on the the second entity. It gets a bit tricky to work out the offsets here, but you may want to have an object hanging from it's end rather than from it's centre point so you need the offset on the object.
* **vecRotation**: is used to build a rotation matrix, relative to the bone you're attaching too (the entity itself if bone=0)
* **PhysicalStrength**: 
* **ConstrainRotation**: specifies whether you wish to constrain rotation as well as position. In most cases the answer will be Yes. Unless you want to have a hangingswinging thing.
* **DoInitialWarp**: ** NOT USED FOR PEDS** specifies whether to warp the object to the specified attach point. If not, then the initial seperation will be used as an allowed give in the attachment (e.g. a rope length)
* **CollideWithEntity**: ** ONLY USED FOR PEDS** of set the two entities will collide with each other once attached
* **AddInitialSeperation**: 
* **RotOrder**: 
