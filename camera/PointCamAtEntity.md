---
ns: CAMERA
aliases: ["0x5640bff86b16e8dc"]
---
## POINT_CAM_AT_ENTITY

```c
// 0x5640BFF86B16E8DC
void POINT_CAM_AT_ENTITY(Camera camera, Entity entity, Vector3 vecOffset, bool OffsetIsRelative);
```

Points the camera at an entity.


## Parameters
* **camera**: 
* **entity**: 
* **vecOffset**: An additional offset to be applied from the look-at position.
* **OffsetIsRelative**: If true, vecOffset is applied relative to the orientation of the entity being pointed at, rather than in world-space.
