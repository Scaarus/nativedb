---
ns: PED
aliases: ["0x4ef47fe21698a8b6"]
---
## SET_PED_DEFENSIVE_AREA_ATTACHED_TO_PED

```c
// 0x4EF47FE21698A8B6
void SET_PED_DEFENSIVE_AREA_ATTACHED_TO_PED(Ped ped, Vector3 1, float fRectangleWidth, bool OrientateWithPed, bool ApplyToSecondaryDefensiveArea);
```

Attaches a defensive area to a ped that other peds will stay inside.

bOrientateWithPed is true, the area will rotate along with the ped. bApplyToSecondaryDefensiveArea makes this command be used with the secondaryfallback defensive area instead of the primary one

