---
ns: GRAPHICS
aliases: ["0xc6eb449e33977f0b"]
---
## START_PARTICLE_FX_LOOPED_ON_ENTITY_BONE

```c
// 0xC6EB449E33977F0B
int START_PARTICLE_FX_LOOPED_ON_ENTITY_BONE(string fxName, Entity entity, Vector3 vecPosition, Vector3 vecRotation, int boneIndex, float scale, bool invertAxisX, bool invertAxisY, bool invertAxisZ);
```

```
Start a looped particle effect on an entity with an offset position and orientation.

STRING

Triggers a named particle effect attached to an entity bone with an offset position. This should only be used with infinitely looping particle effects. The particle effect will then start playing and will need to be stopped by calling STOP_PTFX. The returned id of the particle effect needs to be passed into any other function that needs to be called on it.+
```

## Parameters
* **fxName**: the name of the particle effect to be started ENTITY_INDEX
* **entity**: 
* **vecPosition**: 
* **vecRotation**: 
* **boneIndex**: the bone index to attach the particle effect to (use GET_ENTITY_BONE_INDEX_BY_NAME to get the index) FLOAT
* **scale**: size scale of the effect (default size = 1.0)
* **invertAxisX**: 
* **invertAxisY**: 
* **invertAxisZ**: 
