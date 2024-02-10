---
ns: PED
aliases: ["0x62ab793144de75dc"]
---
## HIDE_PED_BLOOD_DAMAGE_BY_ZONE

```c
// 0x62AB793144DE75DC
void HIDE_PED_BLOOD_DAMAGE_BY_ZONE(Ped ped, int zone, bool enable);
```

Hides (but does not permanently remove) blood from a zone on a ped.

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


It can be called repeatedly to hide blood in multiple zones.


## Parameters
* **ped**: 
* **zone**: the zone on the ped that needs hidden. setting zone to 'PDZ_INVALID' will cause the hideunhide to be applied to all zones on the ped.
* **enable**: true if we're to hide the blood, false if we should show it again
