---
ns: NETWORK
aliases: ["0xa7e30de9272b6d49"]
---
## NETWORK_OVERRIDE_COORDS_AND_HEADING

```c
// 0xA7E30DE9272B6D49
void NETWORK_OVERRIDE_COORDS_AND_HEADING(Entity entity, Vector3 NewPosition, float NewHeading);
```

Sets a ped to a specified heading and position and will set override blend for a period This function is recommended for use when updating a clone every frame to a tightly controlled position such as required for hands clasped with close in camera in arm-wrestling

