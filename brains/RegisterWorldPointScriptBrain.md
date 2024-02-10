---
ns: BRAINS
aliases: ["0x3cdc7136613284bd"]
---
## REGISTER_WORLD_POINT_SCRIPT_BRAIN

```c
// 0x3CDC7136613284BD
void REGISTER_WORLD_POINT_SCRIPT_BRAIN(string pScriptName, float fActivationRange, int SetToWhichThisBrainBelongs);
```

```
Registers a point in a world script point.

This command gives a label to a brain script. The label is used by the artist when placing a 2d effect to launch the brain script. The SCRIPT line in the brain script should read a structure called coords_struct (defined in brains.sch) in the same way as an object brain script expects an OBJECT_INDEX. This structure currently contains up to 3 sets of coordinates. It always has at least one coord which gives the world position around which the brain is centred. For simplicity BrainLabel has been removed so that the name the artits give the 2deffect needs to match the filename of the script.
```

## Parameters
* **pScriptName**: 
* **fActivationRange**: 
* **SetToWhichThisBrainBelongs**: Scripts can define one or more sets to which this brain belongs. The sets should have a value that is a power of 2 (1, 2, 4, 8, 16, 32, ...)
