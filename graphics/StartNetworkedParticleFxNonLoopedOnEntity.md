---
ns: GRAPHICS
aliases: ["0xc95eb1db6e92113d"]
---
## START_NETWORKED_PARTICLE_FX_NON_LOOPED_ON_ENTITY

```c
// 0xC95EB1DB6E92113D
bool START_NETWORKED_PARTICLE_FX_NON_LOOPED_ON_ENTITY(string fxName, Entity entity, Vector3 vecPosition, Vector3 vecRotation, float scale, bool invertAxisX, bool invertAxisY, bool invertAxisZ);
```

Trigger a set piece (non looped) particle effect on an entity with an offset position and orientation.

STRING

Triggers a named particle effect on an entity at an offset position, that will replicate across the network. This should only be used with non-looped particle effects. The particle effect will then play and tidy itself up when finished. There is no access to the particle effect once it has been triggered.


## Parameters
* **fxName**: the name of the particle effect to be triggered ENTITY_INDEX
* **entity**: 
* **vecPosition**: 
* **vecRotation**: 
* **scale**: size scale of the effect (default size = 1.0)
* **invertAxisX**: 
* **invertAxisY**: 
* **invertAxisZ**: 
