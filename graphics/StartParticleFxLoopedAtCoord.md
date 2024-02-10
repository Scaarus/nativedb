---
ns: GRAPHICS
aliases: ["0xe184f4f0dc5910e7"]
---
## START_PARTICLE_FX_LOOPED_AT_COORD

```c
// 0xE184F4F0DC5910E7
int START_PARTICLE_FX_LOOPED_AT_COORD(string fxName, Vector3 vecPosition, Vector3 vecRotation, float scale, bool invertAxisX, bool invertAxisY, bool invertAxisZ, bool localOnly);
```

```
Start a looped particle effect at a world position and orientation.

STRING

Triggers a named particle effect at an world position. This should only be used with infinitely looping particle effects. The particle effect will then start playing and will need to be stopped by calling STOP_PTFX. The returned id of the particle effect needs to be passed into any other function that needs to be called on it.
```

## Parameters
* **fxName**: the name of the particle effect to be started VECTOR
* **vecPosition**: 
* **vecRotation**: 
* **scale**: size scale of the effect (default size = 1.0)
* **invertAxisX**: 
* **invertAxisY**: 
* **invertAxisZ**: 
* **localOnly**: 
