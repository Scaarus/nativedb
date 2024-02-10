---
ns: VEHICLE
aliases: ["0x89d630cf5ea96d23"]
---
## IS_HANDLER_FRAME_LINED_UP_WITH_CONTAINER

```c
// 0x89D630CF5EA96D23
bool IS_HANDLER_FRAME_LINED_UP_WITH_CONTAINER(Vehicle vehicle, Entity entity);
```

Determines if the handler frame is in a good position and orientation with for attaching to the container prop.

This command will complain if the handler already has something attached to its frame.

