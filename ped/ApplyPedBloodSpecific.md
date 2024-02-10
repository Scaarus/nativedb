---
ns: PED
aliases: ["0xef0d582cbf2d9b0f"]
---
## APPLY_PED_BLOOD_SPECIFIC

```c
// 0xEF0D582CBF2D9B0F
void APPLY_PED_BLOOD_SPECIFIC(Ped ped, int component, float u, float v, float rotation, float scale, int forcedFrame, float preAge, string bloodName);
```

Applies ped blood damage on a ped by specifying a specific zone, direct UV offsets, rotation, scale, and initial Age (for animation effects). You can also force a specified frame to be used instead of a randomly chosen one.

you can use the widgets in "Peds/Ped Damage/Test Blood by UV (Script Params)" to test u,v values for different zones, rotations, scales, etc


## Parameters
* **ped**: 
* **component**: 
* **u**: 
* **v**: the UV texture coords for the placement of the decal within the specified zone.
* **rotation**: the angle (in degrees) for the rotation
* **scale**: the scale factor applied to the damage (range is 0.0 to 1.0, based on the MinSizeMaxSize tuning paramters in peddamage.xml)
* **forcedFrame**: 
* **preAge**: the number of seconds to preAge the damage, this allows you for generate an "old wound", using 0.0 will be a usual freash wound.
* **bloodName**: the name of the blood type. this should match an entry in build\dev\common\data\effects\peddamage.xml
