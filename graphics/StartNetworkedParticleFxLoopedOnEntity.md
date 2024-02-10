---
ns: GRAPHICS
aliases: ["0x6f60e89a7b64ee1d"]
---
## START_NETWORKED_PARTICLE_FX_LOOPED_ON_ENTITY

```c
// 0x6F60E89A7B64EE1D
int START_NETWORKED_PARTICLE_FX_LOOPED_ON_ENTITY(string fxName, Entity entity, Vector3 vecPosition, Vector3 vecRotation, float scale, bool invertAxisX, bool invertAxisY, bool invertAxisZ, float colorR, float colorG, float colorB, bool terminateOnOwnerLeave);
```

```
Identical to START_PARTICLE_FX_LOOPED_ON_ENTITY, but also networks the particle effect
```
