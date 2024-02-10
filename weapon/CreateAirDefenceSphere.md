---
ns: WEAPON
aliases: ["0x91ef34584710be99"]
---
## CREATE_AIR_DEFENCE_SPHERE

```c
// 0x91EF34584710BE99
int CREATE_AIR_DEFENCE_SPHERE(Vector3 vPosition, float fRadius, Vector3 vWeaponPosition, Hash weaponHash);
```

```
Any bullets, projectiles or air vehicles that enter this sphere will be destroyed/exploded. Weapon is used to trigger a shotVFX aimed at the sphere intersection position of any bulletsprojectiles to look like they're being shot down. If no weapon hash passed in, sphere will not fire at vehicles, and bulletsprojectiles will only be deleted. Peds inside the sphere will enter the weapon blocked state when trying to aim. MAX_AIR_DEFENCE_ZONES = 10, speak to Blair TruslerDavid Hynd if this needs increasing.

Creates an air defence sphere at the defined position.
```
