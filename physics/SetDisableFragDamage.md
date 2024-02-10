---
ns: PHYSICS
aliases: ["0x01ba3aed21c16cfb"]
---
## SET_DISABLE_FRAG_DAMAGE

```c
// 0x01BA3AED21C16CFB
void SET_DISABLE_FRAG_DAMAGE(Entity entity, bool disableDamage);
```

Prevent a specific prop from damaging, or, allow a specific prop to break when all other of its type cannot.


## Parameters
* **entity**: 
* **disableDamage**: if true, the given entity won't be allowed to damage ever. If false, it will override the flag that prevents all fragments of this type from damaging.
