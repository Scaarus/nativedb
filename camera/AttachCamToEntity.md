---
ns: CAMERA
aliases: ["0xfedb7d269e8c60e3"]
---
## ATTACH_CAM_TO_ENTITY

```c
// 0xFEDB7D269E8C60E3
void ATTACH_CAM_TO_ENTITY(Camera camera, Entity entity, Vector3 vecOffset, bool OffsetIsRelative);
```

```
Attaches a camera to an entity.
```

## Parameters
* **camera**: 
* **entity**: 
* **vecOffset**: An additional offset to be applied from the attach position.
* **OffsetIsRelative**: If true, vecOffset is applied relative to the orientation of the attached entity, rather than in world-space.
