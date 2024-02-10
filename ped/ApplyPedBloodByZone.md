---
ns: PED
aliases: ["0x3311e47b91edcbbc"]
---
## APPLY_PED_BLOOD_BY_ZONE

```c
// 0x3311E47B91EDCBBC
void APPLY_PED_BLOOD_BY_ZONE(Ped ped, int component, float u, float v, string bloodName);
```

Applies new style ped blood damage on a ped by specifying a specific zone and direct UV offsets. (similar to the APPLY_PED_DECORATION()).

you can use the widgets in "Peds/Ped Damage/Test Blood by UV (Interactive)" to test u,v values for different zones, etc


## Parameters
* **ped**: 
* **component**: 
* **u**: 
* **v**: the UV texture coords for the placement of the decal within the specified zone.
* **bloodName**: the name of the blood type. this should match an entry in build\dev\common\data\effects\peddamage.xml
