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
* **zone**: the zone on the ped that needs cleared.
