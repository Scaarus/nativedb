---
ns: CAMERA
aliases: ["0x865908c81a2c22e9"]
---
## DESTROY_CAM

```c
// 0x865908C81A2C22E9
void DESTROY_CAM(Camera camera, bool ShouldApplyAcrossAllThreads);
```

Destroy a single script-controlled camera.


## Parameters
* **camera**: 
* **ShouldApplyAcrossAllThreads**: If true, the specified script-controlled camera is destroyed, no matter which script thread owns it. Note that this can result in conflicts between concurrent script threads, so this must be used with caution.
