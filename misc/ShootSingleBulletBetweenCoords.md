---
ns: MISC
aliases: ["0x867654cbc7606f2c"]
---
## SHOOT_SINGLE_BULLET_BETWEEN_COORDS

```c
// 0x867654CBC7606F2C
void SHOOT_SINGLE_BULLET_BETWEEN_COORDS(Vector3 StartPosition, Vector3 EndPosition, int DamageCaused, bool PerfectAccuracy, Hash weaponHash, Ped ped, bool CreateTraceVfx, bool AllowRumble, float InitialVelocity);
```

Fires an instant hit bullet between the two points.

Damage should be an integer between 0 and 100. It is the amount of damage caused to a ped or vehicle hit by the bullet. The bPerfect accuracy flag sets the bullet at the exact point other wise it applys a spread to the bullets. The weapon type can be projectiles but then the VecEndCoors is the direction and not where it will land The bForceCreateNewProjectileObject flag ensures we create a NEW projectile object and don't use any equipped projectile objects from the firing entity.


## Parameters
* **StartPosition**: 
* **EndPosition**: 
* **DamageCaused**: 
* **PerfectAccuracy**: (Default value: `False`)
* **weaponHash**: (Default value: `Weapontype_Assaultrifle`)
* **ped**: (Default value: `Null`)
* **CreateTraceVfx**: (Default value: `True`)
* **AllowRumble**: (Default value: `True`)
* **InitialVelocity**: 
