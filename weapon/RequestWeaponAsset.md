---
ns: WEAPON
aliases: ["0x5443438f033e29c3"]
---
## REQUEST_WEAPON_ASSET

```c
// 0x5443438F033E29C3
void REQUEST_WEAPON_ASSET(Hash weaponHash, int iWeaponResourceFlags, int ExtraWeaponComponentFlags);
```

Request streaming to load a weapon asset

## ExtraWeaponComponentFlags Values:
| Value | Name |
| --- | --- |
| 0 | None |
| 1 | Flash |
| 2 | Scope |
| 4 | Supp |
| 8 | Sclip2 |
| 16 | Grip |


## Parameters
* **weaponHash**: 
* **iWeaponResourceFlags**: 
* **ExtraWeaponComponentFlags**: Used to load the non-default weapon components.
