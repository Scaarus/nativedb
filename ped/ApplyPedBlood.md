---
ns: PED
aliases: ["0x83f7e01c7b769a26"]
---
## APPLY_PED_BLOOD

```c
// 0x83F7E01C7B769A26
void APPLY_PED_BLOOD(Ped ped, int component, Vector3 vecPos, string bloodName);
```

Applies new style ped blood damage on a ped.

This function assumes you know what component was hit, so I can reverse transform the position into the models space.


## Parameters
* **ped**: 
* **component**: the ragdoll component index of the part of the ped that was hit by the damage (usually from the projectile impact)
* **vecPos**: a position in world space.
* **bloodName**: the name of the blood type. this should match an entry in build\dev\common\data\effects\peddamage.xml
