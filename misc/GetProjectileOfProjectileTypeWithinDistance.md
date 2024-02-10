---
ns: MISC
aliases: ["0x82fde6a57ee4ee44"]
---
## GET_PROJECTILE_OF_PROJECTILE_TYPE_WITHIN_DISTANCE

```c
// 0x82FDE6A57EE4EE44
bool GET_PROJECTILE_OF_PROJECTILE_TYPE_WITHIN_DISTANCE(Ped ped, Hash weaponHash, float distance, bool needsToBeStationary);
```

Checks that a projectile object of the specified type is within distance, from ped and returns the youngest, used to also get the projectile entity

