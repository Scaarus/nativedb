---
ns: PED
aliases: ["0x2208438012482a1a"]
---
## FORCE_PED_AI_AND_ANIMATION_UPDATE

```c
// 0x2208438012482A1A
void FORCE_PED_AI_AND_ANIMATION_UPDATE(Ped ped, bool ForceAIPreCameraUpdate, bool ForceZeroTimestep);
```

Forces a late AI and animation update, to be used only when warping a character and/or instantly changing animation state.

ForceAIPreCameraUpdate forces the ai update to be done before the camera update, only set to TRUE if code have told you to

***this is an expensive command - please speak to AI before using***


## Parameters
* **ped**: 
* **ForceAIPreCameraUpdate**: (Default value: `False`)
* **ForceZeroTimestep**: (Default value: `False`)
