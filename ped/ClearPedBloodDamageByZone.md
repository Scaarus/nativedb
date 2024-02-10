---
ns: PED
aliases: ["0x56e3b78c5408d9f4"]
---
## CLEAR_PED_BLOOD_DAMAGE_BY_ZONE

```c
// 0x56E3B78C5408D9F4
void CLEAR_PED_BLOOD_DAMAGE_BY_ZONE(Ped ped, int zone);
```

clears the blood damage that has been applied to the specified ped on the specified zone.

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
* **zone**: the zone on the ped that needs cleared.
