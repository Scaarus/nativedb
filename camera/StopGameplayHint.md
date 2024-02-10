---
ns: CAMERA
aliases: ["0xf46c581c61718916"]
---
## STOP_GAMEPLAY_HINT

```c
// 0xF46C581C61718916
void STOP_GAMEPLAY_HINT(bool StopImmediately);
```

```
Stops the hint cam running except if its a code gameplay hint.
```

## Parameters
* **StopImmediately**: If TRUE, the hint camera will stop immediately, otherwise it will enter its release phase.
