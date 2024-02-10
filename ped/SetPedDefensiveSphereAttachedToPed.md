---
ns: PED
aliases: ["0xf9b8f91aad3b953e"]
---
## SET_PED_DEFENSIVE_SPHERE_ATTACHED_TO_PED

```c
// 0xF9B8F91AAD3B953E
void SET_PED_DEFENSIVE_SPHERE_ATTACHED_TO_PED(Ped ped, Vector3 vCentre, float fRadius, bool ApplyToSecondaryDefensiveArea);
```

Attaches a defensive area SPHERE to a ped that other peds will stay inside.

bApplyToSecondaryDefensiveArea makes this command be used with the secondary/fallback defensive area instead of the primary one

