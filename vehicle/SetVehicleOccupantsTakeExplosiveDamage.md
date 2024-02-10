---
ns: VEHICLE
aliases: ["0x35bb21de06784373"]
---
## SET_VEHICLE_OCCUPANTS_TAKE_EXPLOSIVE_DAMAGE

```c
// 0x35BB21DE06784373
void SET_VEHICLE_OCCUPANTS_TAKE_EXPLOSIVE_DAMAGE(Vehicle vehicle, bool VehicleOccupantsTakeExplosiveDamage);
```

Ensures occupants will take damage even if their attached vehicle is flagged as invincible/explosion proof. Won't work if ped is flagged as invincible/explosion proof.

Ensure this is reset to false when finished!!!

Sets whether vehicle occupants can take explosive damage if the vehicle is invincibleexplosion proof.

