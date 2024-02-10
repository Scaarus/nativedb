---
ns: VEHICLE
aliases: ["0xa1dd317ea8fd4f29"]
---
## SET_VEHICLE_DAMAGE

```c
// 0xA1DD317EA8FD4F29
void SET_VEHICLE_DAMAGE(Vehicle vehicle, Vector3 DamagePosition, float Damage, float Deformation, bool localDamage);
```

```
Applies damage deformation to a vehicle.

Ths only deforms the car and does not knock off doors etc. the values paassed in to damage and deformation are direct forces.
```

## Parameters
* **vehicle**: 
* **DamagePosition**: is where the damage is applied to the vehicle
* **Damage**: scales how much damage is applied to the vehicle
* **Deformation**: Sets how much the vehicle is deformed by
* **localDamage**: Applys the damage local to the vehicles space.
