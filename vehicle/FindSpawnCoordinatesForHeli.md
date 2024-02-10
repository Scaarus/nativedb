---
ns: VEHICLE
aliases: ["0x8dc9675797123522"]
---
## FIND_SPAWN_COORDINATES_FOR_HELI

```c
// 0x8DC9675797123522
Vector3 FIND_SPAWN_COORDINATES_FOR_HELI();
```

Returns posible spawn position for a heli based on a target ped. Could still be visible by some players, if all found positions (max 5 tries) were on screen for some players, it will return it anyway.

