---
ns: PED
aliases: ["0x9d3151a373974804"]
---
## SET_PED_SPHERE_DEFENSIVE_AREA

```c
// 0x9D3151A373974804
void SET_PED_SPHERE_DEFENSIVE_AREA(Vector3 vCentre, float fRadius, bool UseCenterAsGoToPosition, bool ApplyToSecondaryDefensiveArea);
```

Sets a defensive sphere that a ped will use.

bUseCenterAsGoToPosition will have the ped go to the center position rather than closest position if the cover search fails bApplyToSecondaryDefensiveArea makes this command be used with the secondaryfallback defensive area instead of the primary one


## Parameters
* **vCentre**: 
* **fRadius**: 
* **UseCenterAsGoToPosition**: (Default value: `False`)
* **ApplyToSecondaryDefensiveArea**: (Default value: `False`)
