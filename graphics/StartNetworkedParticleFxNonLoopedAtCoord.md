---
ns: GRAPHICS
aliases: ["0xf56b8137df10135d"]
---
## START_NETWORKED_PARTICLE_FX_NON_LOOPED_AT_COORD

```c
// 0xF56B8137DF10135D
bool START_NETWORKED_PARTICLE_FX_NON_LOOPED_AT_COORD(string fxName, Vector3 vecPosition, Vector3 vecRotation, float scale, bool invertAxisX, bool invertAxisY, bool invertAxisZ, bool ignoreScopeChecks);
```

```
Trigger a set piece (non looped) particle effect at a world position and orientation.

STRING

Triggers a named particle effect at a world position, that will replicate across the network. This should only be used with non-looped particle effects. The particle effect will then play and tidy itself up when finished. There is no access to the particle effect once it has been triggered.
```

## Parameters
* **fxName**: the name of the particle effect to be triggered VECTOR
* **vecPosition**: 
* **vecRotation**: 
* **scale**: size scale of the effect (default size = 1.0)
* **invertAxisX**: 
* **invertAxisY**: 
* **invertAxisZ**: 
* **ignoreScopeChecks**: use this ONLY for the ion cannon effects, otherwise request permission from network code
