---
ns: PED
aliases: ["0x1cce141467ff42a2"]
---
## SET_PED_CAN_SMASH_GLASS

```c
// 0x1CCE141467FF42A2
void SET_PED_CAN_SMASH_GLASS(Ped ped, bool CanSmashGlassFlagRagdoll, bool CanSmashGlassFlagWeapon);
```

Call every frame to make the ped's ragdoll or weapon bounds shatter glass when in contact


## Parameters
* **ped**: 
* **CanSmashGlassFlagRagdoll**: If TRUE then if the ped's ragdoll bounds comes in contact with breakable glass, the glass will break. Ped does need to be in ragdoll state
* **CanSmashGlassFlagWeapon**: If TRUE then if the ped's weapon bounds comes in contact with breakable glass, the glass will break. Ped does need to be in ragdoll state
