---
ns: PED
aliases: ["0xaf8a94ede7712bef"]
---
## SET_PED_MOVEMENT_CLIPSET

```c
// 0xAF8A94EDE7712BEF
void SET_PED_MOVEMENT_CLIPSET(Ped ped, string ClipSet, float BlendDuration);
```

Makes the ped use a different movement clipset e.g for making a fat ped run faster The default movement clipset is defined in peds.meta under <MovementClipSet> DON'T FORGET to stream in the new clipset before calling this!!


## Parameters
* **ped**: 
* **ClipSet**: 
* **BlendDuration**: (Default value: `0`)
