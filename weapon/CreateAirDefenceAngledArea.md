---
ns: WEAPON
aliases: ["0x9da58cdbf6bdbc08"]
---
## CREATE_AIR_DEFENCE_ANGLED_AREA

```c
// 0x9DA58CDBF6BDBC08
int CREATE_AIR_DEFENCE_ANGLED_AREA(Vector3 Position1, Vector3 Position2, float AreaWidth, Vector3 vWeaponPosition, Hash weaponHash);
```

Any bullets, projectiles or air vehicles that enter this angled area will be destroyed/exploded. Weapon is used to trigger a shotVFX aimed at the area intersection position of any bulletsprojectiles to look like they're being shot down. If no weapon hash passed in, angled area will not fire at vehicles, and bulletsprojectiles will only be deleted. Peds inside the angled area will enter the weapon blocked state when trying to aim. MAX_AIR_DEFENCE_ZONES = 10, speak to Blair TruslerDavid Hynd if this needs increasing.

Creates an air defence angled area at the defined position.


## Parameters
* **Position1**: 
* **Position2**: 
* **AreaWidth**: 
* **vWeaponPosition**: 
* **weaponHash**: (Default value: `Weapontype_Dlc_Air_Defence_Gun`)
