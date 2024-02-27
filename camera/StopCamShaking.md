---
ns: CAMERA
aliases: ["0xbdecf64367884ac3"]
---
## STOP_CAM_SHAKING

```c
// 0xBDECF64367884AC3
void STOP_CAM_SHAKING(Camera camera, bool StopImmediately);
```

Stop the camera shaking.


## Parameters
* **camera**: 
* **StopImmediately**: If TRUE, the shake will stop immediately, otherwise it will enter its release phase and fade out. (Default value: `False`)
