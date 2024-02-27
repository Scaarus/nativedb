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

## Values for `zone`:
| Value | Name |
| --- | --- |
| 0 | Torso |
| 1 | Head |
| 2 | Left Arm |
| 3 | Right Arm |
| 4 | Left Leg |
| 5 | Right Leg |
| 6 | Medals |
| 7 | Invalid |


## Parameters
* **ped**: 
* **zone**: the zone on the ped that needs cleared or 'PDZ_INVALID' for all zones
* **damageDecalName**: name of the decal, or 'ALL' for all Damage Decals
