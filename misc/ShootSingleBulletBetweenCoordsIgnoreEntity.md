---
ns: MISC
aliases: ["0xe3a7742e0b7a2f8b"]
---
## SHOOT_SINGLE_BULLET_BETWEEN_COORDS_IGNORE_ENTITY

```c
// 0xE3A7742E0B7A2F8B
void SHOOT_SINGLE_BULLET_BETWEEN_COORDS_IGNORE_ENTITY(Vector3 StartPosition, Vector3 EndPosition, int DamageCaused, bool PerfectAccuracy, Hash weaponHash, Ped ped, bool CreateTraceVfx, bool AllowRumble, float InitialVelocity, Entity entity, Entity entity);
```

Fires an instant hit bullet between the two points taking into account an entity to ignore for damage.

Variant of [`SHOOT_SINGLE_BULLET_BETWEEN_COORDS`](#_0x867654CBC7606F2C). You can specify an ignore entity here to disable damage against it. The bForceCreateNewProjectileObject flag ensures we create a NEW projectile object and don't use any equipped projectile objects from the firing entity. Setting the TargetEntity parameter will enable homing code if the weapon is a rocket.


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
* **entity**: (Default value: `Null`)
* **entity**: (Default value: `Null`)
