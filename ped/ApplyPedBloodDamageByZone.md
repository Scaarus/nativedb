---
ns: PED
aliases: ["0x816f6981c60bf53b"]
---
## APPLY_PED_BLOOD_DAMAGE_BY_ZONE

```c
// 0x816F6981C60BF53B
void APPLY_PED_BLOOD_DAMAGE_BY_ZONE(Ped ped, int zone, float u, float v, int type);
```

Applies new style ped blood damage on a ped by specifying a specific zone and direct UV offsets. (similar to the APPLY_PED_DECORATION()).

## zone Values:
| Value | Name |
| --- | --- |
| 0 | Torso |
| 160 | Head |
| 161 | Left Arm |
| 162 | Right Arm |
| 163 | Left Leg |
| 164 | Right Leg |
| 165 | Medals |
| 166 | Invalid |


## type Values:
| Value | Name |
| --- | --- |
| 0 | Bullet Small |
| 167 | Bullet Large Larger Caliber Bullet Wound |
| 168 | Shotgun Small Close Range Shotgun Splatter Wound? |
| 169 | Shotgun Large Far Shotgun Splatter Wound |
| 170 | Stab A Stab Style Wound (Streches Along The Suppolied Direction) |


you can use the widgets in "Peds/Ped Damage/Test Blood by UV" to test u,v values for different zones, etc


## Parameters
* **ped**: 
* **zone**: the zone of the ped to apply the blood damage (see PED_DECORATION_ZONE in commands_ped.sch) u &
* **u**: 
* **v**: the UV texture coords for the placement of the decal within the specified zone.
* **type**: the blood damage type ( see PED_BLOOD_DAMAGE_TYPE in commands_ped.sch)
