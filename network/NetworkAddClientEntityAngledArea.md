---
ns: NETWORK
aliases: ["0x2b1c623823db0d9d"]
---
## NETWORK_ADD_CLIENT_ENTITY_ANGLED_AREA

```c
// 0x2B1C623823DB0D9D
int NETWORK_ADD_CLIENT_ENTITY_ANGLED_AREA(Vector3 Start, Vector3 End, float fAreaWidth);
```

Adds an entity angled area with the specified start and end points that will be cleaned up when the player that created it leaves the session The return value is a script ID that can be used to refer to the same entity area again

