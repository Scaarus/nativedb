---
ns: PED
aliases: ["0x2622e35b77d3aca2"]
---
## SET_PED_WEAPON_MOVEMENT_CLIPSET

```c
// 0x2622E35B77D3ACA2
void SET_PED_WEAPON_MOVEMENT_CLIPSET(Ped ped, string ClipSet);
```

Make the ped use different weapon clipset when walking around. e.g. calling this with the rifle movement clipset would cause the ped to always walk around as if it were carrying a rifle, regardless of the weapon equipped. Note, this only affects the peds animation when walking around normally, not when strafing or aiming with the weapon. Weapon movement clipset are defined in weapons.meta DON'T FORGET to stream in the new clipset before calling this!!

