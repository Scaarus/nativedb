---
ns: CAMERA
aliases: ["0x2238e588e588a6d7"]
---
## STOP_CINEMATIC_CAM_SHAKING

```c
// 0x2238E588E588A6D7
void STOP_CINEMATIC_CAM_SHAKING(bool StopImmediately);
```

```
Stop the active cinematic camera shake.
```

## Parameters
* **StopImmediately**: If TRUE, the shake will stop immediately, otherwise it will enter its release phase and fade out.
