---
ns: WEAPON
aliases: ["0x6c4d0409ba1a2bc2"]
---
## GET_PED_LAST_WEAPON_IMPACT_COORD

```c
// 0x6C4D0409BA1A2BC2
bool GET_PED_LAST_WEAPON_IMPACT_COORD(Ped ped, Vector3 ImpactCoord);
```

Checks if it can and gets the last position a weapon was impacted at.

This command should be called every frame as the the last valid result only is reurned that frame else it returns 0.

