---
ns: PED
aliases: ["0x1216e0bfa72cc703"]
---
## REQUEST_RAGDOLL_BOUNDS_UPDATE

```c
// 0x1216E0BFA72CC703
void REQUEST_RAGDOLL_BOUNDS_UPDATE(Ped ped, int framesToUpdateBounds);
```

You should call this at least one frame prior to requesting a bound position or activating a ragdoll from script.

framesToUpdateBounds gets set as a u16 in code, so make sure that the input value in between 0 and 65535.

Instructs the game to update ragdoll bounds for animated AI peds for a specified number of frames.

