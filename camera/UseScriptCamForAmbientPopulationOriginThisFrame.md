---
ns: CAMERA
aliases: ["0x271401846bd26e92"]
---
## USE_SCRIPT_CAM_FOR_AMBIENT_POPULATION_ORIGIN_THIS_FRAME

```c
// 0x271401846BD26E92
void USE_SCRIPT_CAM_FOR_AMBIENT_POPULATION_ORIGIN_THIS_FRAME(bool Vehicles, bool Peds);
```

```
Sets the ambient ped & vehicle population spawning origin to be based around the active scripted camera for this frame This will prevent vehicles from being created close to the camera andor on-screen Call this repeatedly during scripted camera sequences where this behaviour is required.
```
