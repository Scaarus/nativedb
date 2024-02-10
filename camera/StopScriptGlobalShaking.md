---
ns: CAMERA
aliases: ["0x1c9d7949fa533490"]
---
## STOP_SCRIPT_GLOBAL_SHAKING

```c
// 0x1C9D7949FA533490
void STOP_SCRIPT_GLOBAL_SHAKING(bool StopImmediately);
```

```
Stop the active scripted camera global shake.
```

## Parameters
* **StopImmediately**: If TRUE, the shake will stop immediately, otherwise it will enter its release phase and fade out.
