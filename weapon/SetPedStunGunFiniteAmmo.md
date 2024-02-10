---
ns: WEAPON
aliases: ["0x24c024ba8379a70a"]
---
## SET_PED_STUN_GUN_FINITE_AMMO

```c
// 0x24C024BA8379A70A
void SET_PED_STUN_GUN_FINITE_AMMO(Ped ped, bool SetFinite);
```

Set the specified ped to have finite ammo for WEAPON_STUNGUN, overriding metadata InfiniteAmmo value Natives that set ammo values on WEAPON_STUNGUNAMMO_STUNGUN will be IGNORED if finite ammo is not set by this native

