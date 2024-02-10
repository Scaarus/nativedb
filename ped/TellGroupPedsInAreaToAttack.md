---
ns: PED
aliases: ["0xad27d957598e49e9"]
---
## TELL_GROUP_PEDS_IN_AREA_TO_ATTACK

```c
// 0xAD27D957598E49E9
void TELL_GROUP_PEDS_IN_AREA_TO_ATTACK(Ped ped, Vector3 scrVectorCenterCoords, float radius, Hash relGroup);
```

Sets all peds of a relationship group in a given sphere (defined by a vector position and radius) to attack the target disliked ped.

relGroup is the hash of the relationship group you want to have attack the (disliked) target.

