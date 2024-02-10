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
| 60 | Front Right |
| 61 | Rear Left |
| 62 | Rear Right |
| 63 | Bonnet |
| 64 | Boot |

