---
ns: GRAPHICS
aliases: ["0x25129531f77b9ed3"]
---
## START_PARTICLE_FX_NON_LOOPED_AT_COORD

```c
// 0x25129531F77B9ED3
bool START_PARTICLE_FX_NON_LOOPED_AT_COORD(string fxName, Vector3 vecPosition, Vector3 vecRotation, float scale, bool invertAxisX, bool invertAxisY, bool invertAxisZ);
```

```
Trigger a set piece (non looped) particle effect at a world position and orientation.

STRING

Triggers a named particle effect at a world position. This should only be used with non-looped particle effects. The particle effect will then play and tidy itself up when finished. There is no access to the particle effect once it has been triggered.
```

## Parameters
* **fxName**: the name of the particle effect to be triggered VECTOR
* **vecPosition**: 
* **vecRotation**: 
* **scale**: size scale of the effect (default size = 1.0)
* **invertAxisX**: 
* **invertAxisY**: 
* **invertAxisZ**: 
