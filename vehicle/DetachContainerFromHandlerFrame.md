---
ns: VEHICLE
aliases: ["0x7c0043fdff6436bc"]
---
## DETACH_CONTAINER_FROM_HANDLER_FRAME

```c
// 0x7C0043FDFF6436BC
void DETACH_CONTAINER_FROM_HANDLER_FRAME(Vehicle vehicle);
```

```
Detaches any container which has been attached to the handler's frame. It is up to the script what to do with the objects once detached.

This command will complain if nothing is attached to the handler's frame.
```
