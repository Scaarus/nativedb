---
ns: NETWORK
aliases: ["0x25b99872d588a101"]
---
## NETWORK_ADD_CLIENT_ENTITY_AREA

```c
// 0x25B99872D588A101
int NETWORK_ADD_CLIENT_ENTITY_AREA(Vector3 Start, Vector3 End);
```

Adds an entity area with the specified start and end points that will be cleaned up when the player that created it leaves the session The return value is a script ID that can be used to refer to the same entity area again

