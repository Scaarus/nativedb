---
ns: MISC
aliases: ["0xbfe5756e7407064a"]
---
## SHOOT_SINGLE_BULLET_BETWEEN_COORDS_IGNORE_ENTITY_NEW

```c
// 0xBFE5756E7407064A
void SHOOT_SINGLE_BULLET_BETWEEN_COORDS_IGNORE_ENTITY_NEW(Vector3 StartPosition, Vector3 EndPosition, int DamageCaused, bool PerfectAccuracy, Hash weaponHash, Ped ped, bool CreateTraceVfx, bool AllowRumble, float InitialVelocity, Entity entity, bool ForceCreateNewProjectileObject, bool DisablePlayerCoverStartAdjustment, Entity entity, bool DoDeadCheck, bool FreezeProjectileWaitingOnCollision, bool SetIgnoreCollisionEntity, bool IgnoreCollisionResetNoBB);
```

Fires an instant hit bullet between the two points taking into account an entity to ignore for damage.

Variant of [`SHOOT_SINGLE_BULLET_BETWEEN_COORDS`](#_0x867654CBC7606F2C). You can specify an ignore entity here to disable damage against it. The bForceCreateNewProjectileObject flag ensures we create a NEW projectile object and don't use any equipped projectile objects from the firing entity. Setting the TargetEntity parameter will enable homing code if the weapon is a rocket. Set bIgnoreCollisionResetNoBB to ignore collision until the projectile leaves the BoundingBox of the given IgnoreEntity


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
* **ForceCreateNewProjectileObject**: (Default value: `False`)
* **DisablePlayerCoverStartAdjustment**: (Default value: `False`)
* **entity**: (Default value: `Null`)
* **DoDeadCheck**: (Default value: `True`)
* **FreezeProjectileWaitingOnCollision**: (Default value: `False`)
* **SetIgnoreCollisionEntity**: (Default value: `False`)
* **IgnoreCollisionResetNoBB**: (Default value: `False`)
