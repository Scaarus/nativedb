---
ns: CAMERA
aliases: ["0x8e5fb15663f79120"]
---
## DESTROY_ALL_CAMS

```c
// 0x8E5FB15663F79120
void DESTROY_ALL_CAMS(bool ShouldApplyAcrossAllThreads);
```

```
Destroy ALL script-controlled cameras.
```

## Parameters
* **ShouldApplyAcrossAllThreads**: If true, ALL script-controlled cameras are destroyed, no matter which script thread owns them. Note that this can result in conflicts between concurrent script threads, so this must be used with caution.
