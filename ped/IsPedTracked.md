---
ns: PED
aliases: ["0x4c5e1f087cd10bb7"]
---
## IS_PED_TRACKED

```c
// 0x4C5E1F087CD10BB7
bool IS_PED_TRACKED(Ped ped);
```

Checks whether a ped is being tracked Should be used before calling GET_TRACKED_PED_PIXELCOUNT to make sure the ped is being tracked - if the ped is not tracked, GET_TRACKED_PED_PIXELCOUNT will asert.

