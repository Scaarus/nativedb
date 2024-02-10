---
ns: MISC
aliases: ["0x2d4259f1feb81da9"]
---
## ADD_DISPATCH_SPAWN_SPHERE_BLOCKING_AREA

```c
// 0x2D4259F1FEB81DA9
int ADD_DISPATCH_SPAWN_SPHERE_BLOCKING_AREA(Vector3 vCenter, float fRadius);
```

```
Prevents dispatch spawning in the requested area. Returns a handle which can be used to remove the area.

Prevents dispatch spawning in the requested area. MAX allowed areas is 2. Let code know if that needs increasing. Shares storage with angled blocking areas
```
