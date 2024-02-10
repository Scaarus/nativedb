---
ns: PED
aliases: ["0x397c38aa7b4a5f83"]
---
## APPLY_PED_DAMAGE_DECAL

```c
// 0x397C38AA7B4A5F83
void APPLY_PED_DAMAGE_DECAL(Ped ped, int zone, float u, float v, float rotation, float scale, float alpha_param, int forceFrame, bool fadeIn, string damageDecalName);
```

Applies a ped damage decoration (decal) to the ped, using the data defined in the peddamage.xml tuning file. the decal could be a tatoo, dirt a scar, etc.

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


you can use the widgets in "Peds/Ped Damage/Test Damage Decals by UV (Interactive)" to test u,v values for different zones, etc


## Parameters
* **ped**: 
* **zone**: the zone of the ped to apply the decorations (see PED_DECORATION_ZONE in commands_ped.sch) u &
* **u**: 
* **v**: the UV texture coords for the placement of the decal within the specified zone.
* **rotation**: the rotation of the decoration blit around it's center, in degrees.
* **scale**: the scale of the decoration blit. (range is 0.0 to 1.0, based on the Size tuning paramter in peddamage.xml)
* **alpha_param**: the alpha value use when applying the decal
* **forceFrame**: specify a specific frame fromthe texture grid.
* **fadeIn**: should the decal fade in or just "pop" on
* **damageDecalName**: 
