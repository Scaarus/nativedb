---
ns: WEAPON
aliases: ["0xb4c8d77c80c0421e"]
---
## SET_PED_SHOOT_ORDNANCE_WEAPON

```c
// 0xB4C8D77C80C0421E
Entity SET_PED_SHOOT_ORDNANCE_WEAPON(Ped ped, float fProjectileLifeTime);
```

```
Fires off ordnance weapon and returns the projectile object to script for control

fProjectileLifeTime will determine how long (in secs) the projectile will live. By default the life time is infinite. Projectile will still be destroyed on contact with any physical body.
```
