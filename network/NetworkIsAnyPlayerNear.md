---
ns: NETWORK
aliases: ["0x2e4c123d1c8a710e"]
---
## NETWORK_IS_ANY_PLAYER_NEAR

```c
// 0x2E4C123D1C8A710E
bool NETWORK_IS_ANY_PLAYER_NEAR(int retPlayerIds, int retNumber, Vector3 pos, float radius, bool in3d);
```

Returns TRUE if participants were found near coordinates.


## Parameters
* **retPlayerIds**: Returns the global player index. Each bit represents one player. Look for the bits that are set to know the player global player index.
* **retNumber**: Returns the number of players that are near.
* **pos**: center point for the search.
* **radius**: radius for the search.
* **in3d**: make search using Z coordinate as well.
