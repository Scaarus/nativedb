---
ns: INTERIORS
aliases: ["0x82ebb79e258fa2b7"]
---
## RETAIN_ENTITY_IN_INTERIOR

```c
// 0x82EBB79E258FA2B7
void RETAIN_ENTITY_IN_INTERIOR(Interior_Instance interior_instance);
```

```
Add the given entity to the retain list for the given interior. When the interior is loaded, the retain list will be automatically inserted into it.

Entities owned by scripts and in interiors are automatically placed onto the retain list when the interior is unloaded.
```
