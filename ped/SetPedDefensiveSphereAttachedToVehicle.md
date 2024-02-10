---
ns: PED
aliases: ["0xe4723db6e736ccff"]
---
## SET_PED_DEFENSIVE_SPHERE_ATTACHED_TO_VEHICLE

```c
// 0xE4723DB6E736CCFF
void SET_PED_DEFENSIVE_SPHERE_ATTACHED_TO_VEHICLE(Vehicle vehicle, Vector3 vCentre, float fRadius, bool ApplyToSecondaryDefensiveArea);
```

Attaches a defensive area SPHERE to a vehicle that the ped will stay inside.

bApplyToSecondaryDefensiveArea makes this command be used with the secondary/fallback defensive area instead of the primary one

