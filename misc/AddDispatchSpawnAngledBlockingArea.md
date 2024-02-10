---
ns: MISC
aliases: ["0x918c7b2d2ff3928b"]
---
## ADD_DISPATCH_SPAWN_ANGLED_BLOCKING_AREA

```c
// 0x918C7B2D2FF3928B
int ADD_DISPATCH_SPAWN_ANGLED_BLOCKING_AREA(Vector3 vStart, Vector3 vEnd, float fWidth);
```

```
Prevents dispatch spawning in the requested area. Returns a handle which can be used to remove the area.

Prevents dispatch spawning in the requested area. MAX allowed areas is 2. Let code know if that needs increasing. Shares storage with sphere blocking areas
```
