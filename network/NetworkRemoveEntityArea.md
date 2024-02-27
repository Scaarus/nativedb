---
ns: NETWORK
aliases: ["0x93cf869baa0c4874"]
---
## NETWORK_REMOVE_ENTITY_AREA

```c
// 0x93CF869BAA0C4874
bool NETWORK_REMOVE_ENTITY_AREA(int areaID);
```

Removes the specified entity area. This is not required on script termination - these will be cleaned up in code. The areaID is the ID returned by [`NETWORK_ADD_ENTITY_AREA`](#_0x494C8FB299290269) Returns whether this areaID was found or not

