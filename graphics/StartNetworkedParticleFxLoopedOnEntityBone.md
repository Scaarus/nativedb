---
ns: GRAPHICS
aliases: ["0xdde23f30cc5a0f03"]
---
## START_NETWORKED_PARTICLE_FX_LOOPED_ON_ENTITY_BONE

```c
// 0xDDE23F30CC5A0F03
int START_NETWORKED_PARTICLE_FX_LOOPED_ON_ENTITY_BONE(string fxName, Entity entity, Vector3 vecPosition, Vector3 vecRotation, int boneIndex, float scale, bool invertAxisX, bool invertAxisY, bool invertAxisZ, float colorR, float colorG, float colorB, bool terminateOnOwnerLeave);
```

Identical to [`START_PARTICLE_FX_LOOPED_ON_ENTITY_BONE`](#_0xC6EB449E33977F0B), but also networks the particle effect


## Parameters
* **fxName**: 
* **entity**: 
* **vecPosition**: 
* **vecRotation**: 
* **boneIndex**: 
* **scale**: (Default value: `1`)
* **invertAxisX**: (Default value: `False`)
* **invertAxisY**: (Default value: `False`)
* **invertAxisZ**: (Default value: `False`)
* **colorR**: (Default value: `1`)
* **colorG**: (Default value: `1`)
* **colorB**: (Default value: `1`)
* **terminateOnOwnerLeave**: (Default value: `False`)
