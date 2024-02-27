---
ns: CAMERA
aliases: ["0x202a5ed9ce01d6e7"]
---
## HARD_ATTACH_CAM_TO_ENTITY

```c
// 0x202A5ED9CE01D6E7
void HARD_ATTACH_CAM_TO_ENTITY(Camera camera, Entity entity, Vector3 vecRotationOffset, Vector3 vecPositionOffset, bool OffsetIsRelative);
```

Attaches a camera to an entity's full matrix.


## Parameters
* **camera**: 
* **entity**: 
* **vecRotationOffset**: An additional rotational offset to be applied from the attach entity rotation (x=yaw, y=pitch, z=roll).
* **vecPositionOffset**: An additional offset to be applied from the attach position.
* **OffsetIsRelative**: If true, vecOffset is applied relative to the orientation of the attached entity, rather than in world-space. (Default value: `True`)
