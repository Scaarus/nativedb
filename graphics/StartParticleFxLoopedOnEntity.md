---
ns: GRAPHICS
aliases: ["0x1ae42c1660fd6517"]
---
## START_PARTICLE_FX_LOOPED_ON_ENTITY

```c
// 0x1AE42C1660FD6517
int START_PARTICLE_FX_LOOPED_ON_ENTITY(string fxName, Entity entity, Vector3 vecPosition, Vector3 vecRotation, float scale, bool invertAxisX, bool invertAxisY, bool invertAxisZ);
```

Start a looped particle effect on an entity with an offset position and orientation.

STRING

Triggers a named particle effect attached to an entity with an offset position. This should only be used with infinitely looping particle effects. The particle effect will then start playing and will need to be stopped by calling STOP_PTFX. The returned id of the particle effect needs to be passed into any other function that needs to be called on it.+


## Parameters
* **fxName**: the name of the particle effect to be started ENTITY_INDEX
* **entity**: 
* **vecPosition**: 
* **vecRotation**: 
* **scale**: size scale of the effect (default size = 1.0) (Default value: `1`)
* **invertAxisX**: (Default value: `False`)
* **invertAxisY**: (Default value: `False`)
* **invertAxisZ**: (Default value: `False`)
