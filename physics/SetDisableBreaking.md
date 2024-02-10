---
ns: PHYSICS
aliases: ["0x5cec1a84620e7d5b"]
---
## SET_DISABLE_BREAKING

```c
// 0x5CEC1A84620E7D5B
void SET_DISABLE_BREAKING(Entity entity, bool disableBreaking);
```

```
Prevent a specific prop from breaking, or, allow a specific prop to break when all other of its type cannot.
```

## Parameters
* **entity**: 
* **disableBreaking**: if true, the given entity won't be allowed to break ever. If false, it will override the flag that prevents all fragments of this type from breaking.
