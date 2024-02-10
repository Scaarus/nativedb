---
ns: CAMERA
aliases: ["0x324c5aa411da7737"]
---
## STOP_CUTSCENE_CAM_SHAKING

```c
// 0x324C5AA411DA7737
void STOP_CUTSCENE_CAM_SHAKING(bool StopImmediately);
```

Stop the active cutscene camera shake.


## Parameters
* **StopImmediately**: If TRUE, the shake will stop immediately, otherwise it will enter its release phase and fade out.
