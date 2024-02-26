---
ns: VEHICLE
aliases: ["0x6a98c2ecf57fa5d4"]
---
## ATTACH_CONTAINER_TO_HANDLER_FRAME_WHEN_LINED_UP

```c
// 0x6A98C2ECF57FA5D4
void ATTACH_CONTAINER_TO_HANDLER_FRAME_WHEN_LINED_UP(Vehicle vehicle, Entity entity);
```

Attaches an instance of the special container prop used with the handler onto the handler's frame by lerping it instead of warping it so the caller is responsible for first checking that the container is in position with [IS_HANDLER_FRAME_LINED_UP_WITH_CONTAINER](#_0x89D630CF5EA96D23).

This command will complain if the handler already has something attached to its frame.

