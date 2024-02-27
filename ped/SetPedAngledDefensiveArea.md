---
ns: PED
aliases: ["0xc7f76df27a5045a1"]
---
## SET_PED_ANGLED_DEFENSIVE_AREA

```c
// 0xC7F76DF27A5045A1
void SET_PED_ANGLED_DEFENSIVE_AREA(Vector3 1, float fRectangleWidth, bool UseCenterAsGoToPosition, bool ApplyToSecondaryDefensiveArea);
```

Sets a non-axis aligned defensive area that a ped will use

bUseCenterAsGoToPosition will have the ped go to the center position rather than closest position if the cover search fails bApplyToSecondaryDefensiveArea makes this command be used with the secondaryfallback defensive area instead of the primary one


## Parameters
* **1**: 
* **fRectangleWidth**: 
* **UseCenterAsGoToPosition**: (Default value: `False`)
* **ApplyToSecondaryDefensiveArea**: (Default value: `False`)
