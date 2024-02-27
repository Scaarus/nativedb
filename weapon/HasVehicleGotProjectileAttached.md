---
ns: WEAPON
aliases: ["0x717c8481234e3b88"]
---
## HAS_VEHICLE_GOT_PROJECTILE_ATTACHED

```c
// 0x717C8481234E3B88
bool HAS_VEHICLE_GOT_PROJECTILE_ATTACHED(Ped ped, Vehicle vehicle, Hash weaponHash, int DoorNumber);
```

Query whether the specified ped has any projectiles attached to the specified vehicle of the specified type (0 for any type)

## DoorNumber Values:
| Value | Name |
| --- | --- |
| -1 | Invalid |
| 0 | Front Left |
| 1 | Front Right |
| 2 | Rear Left |
| 3 | Rear Right |
| 4 | Bonnet |
| 5 | Boot |


## Parameters
* **ped**: 
* **vehicle**: 
* **weaponHash**: (Default value: `0`)
* **DoorNumber**: (Default value: `Invalid`)
