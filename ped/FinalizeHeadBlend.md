---
ns: PED
aliases: ["0x4668d80430d6c299"]
---
## FINALIZE_HEAD_BLEND

```c
// 0x4668D80430D6C299
void FINALIZE_HEAD_BLEND(Ped ped);
```

Finalizes a head blend and releases source assets. Call this when a ped is finished. More...

This function will release source assets and should be called when a ped is finished and no more changes will be applied. For example, when creating a ped and the player has finished selecting everythin this function should be called when no more changes can be done to the player. It also needs to be called after the player has finished buying clothes or tattoos and other similar cases.

