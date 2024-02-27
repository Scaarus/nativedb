---
ns: GRAPHICS
aliases: ["0x02b1f2a72e0f5325"]
---
## START_PARTICLE_FX_NON_LOOPED_ON_ENTITY_BONE

```c
// 0x02B1F2A72E0F5325
bool START_PARTICLE_FX_NON_LOOPED_ON_ENTITY_BONE(string fxName, Entity entity, Vector3 vecPosition, Vector3 vecRotation, int boneIndex, float scale, bool invertAxisX, bool invertAxisY, bool invertAxisZ);
```

Trigger a set piece (non looped) particle effect on an entity with an offset position and orientation.

STRING

Triggers a named particle effect on an entity bone at an offset position. This should only be used with non-looped particle effects. The particle effect will then play and tidy itself up when finished. There is no access to the particle effect once it has been triggered.


## Parameters
* **fxName**: the name of the particle effect to be triggered ENTITY_INDEX
* **entity**: 
* **vecPosition**: 
* **vecRotation**: 
* **boneIndex**: the bone index to attach the particle effect to (use GET_ENTITY_BONE_INDEX_BY_NAME to get the index) FLOAT
* **scale**: size scale of the effect (default size = 1.0) (Default value: `1`)
* **invertAxisX**: (Default value: `False`)
* **invertAxisY**: (Default value: `False`)
* **invertAxisZ**: (Default value: `False`)
