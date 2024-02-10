---
ns: NETWORK
aliases: ["0x2e4c123d1c8a710e"]
---
## NETWORK_IS_ANY_PLAYER_NEAR

```c
// 0x2E4C123D1C8A710E
bool NETWORK_IS_ANY_PLAYER_NEAR(Vector3 pos, float radius, bool in3d);
```

Returns TRUE if participants were found near coordinates.


## Parameters
* **pos**: center point for the search.
* **radius**: radius for the search.
* **in3d**: make search using Z coordinate as well.
