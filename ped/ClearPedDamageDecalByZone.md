---
ns: PED
aliases: ["0x523c79aeefcc4a2a"]
---
## CLEAR_PED_DAMAGE_DECAL_BY_ZONE

```c
// 0x523C79AEEFCC4A2A
void CLEAR_PED_DAMAGE_DECAL_BY_ZONE(Ped ped, int zone, string damageDecalName);
```

clears the Damage damage that has been applied to the specified ped on the specified zone.

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


## Parameters
* **ped**: 
* **zone**: the zone on the ped that needs cleared or 'PDZ_INVALID' for all zones
* **damageDecalName**: name of the decal, or 'ALL' for all Damage Decals
