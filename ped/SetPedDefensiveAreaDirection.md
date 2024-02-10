---
ns: PED
aliases: ["0x413c6c763a4affad"]
---
## SET_PED_DEFENSIVE_AREA_DIRECTION

```c
// 0x413C6C763A4AFFAD
void SET_PED_DEFENSIVE_AREA_DIRECTION(Vector3 vDefendFromPos, bool ApplyToSecondaryDefensiveArea);
```

```
Removes any defensive area given to the ped.

vDefendFromPos appears to be a position rather than a direction. It's hard to tell from the code but it looks like it's the world position to aim at. bApplyToSecondaryDefensiveArea makes this command be used with the secondaryfallback defensive area instead of the primary one
```
