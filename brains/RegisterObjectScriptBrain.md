---
ns: BRAINS
aliases: ["0x0be84c318ba6ec22"]
---
## REGISTER_OBJECT_SCRIPT_BRAIN

```c
// 0x0BE84C318BA6EC22
void REGISTER_OBJECT_SCRIPT_BRAIN(string pScriptName, Hash modelHash, int PercentageChance, float fActivationRange, int ObjectGroupingID, int SetToWhichThisBrainBelongs);
```

Associates a script brain with a certain object model.

Pass in -1 to ignore the object grouping.


## Parameters
* **pScriptName**: 
* **modelHash**: 
* **PercentageChance**: 
* **fActivationRange**: 
* **ObjectGroupingID**: 
* **SetToWhichThisBrainBelongs**: Scripts can define one or more sets to which this brain belongs. The sets should have a value that is a power of 2 (1, 2, 4, 8, 16, 32, ...)
