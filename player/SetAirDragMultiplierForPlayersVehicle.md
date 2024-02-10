---
ns: PLAYER
aliases: ["0xca7dc8329f0a1e9e"]
---
## SET_AIR_DRAG_MULTIPLIER_FOR_PLAYERS_VEHICLE

```c
// 0xCA7DC8329F0A1E9E
void SET_AIR_DRAG_MULTIPLIER_FOR_PLAYERS_VEHICLE(Player player, float fDragMult);
```

```
Force higher air drag mult on any car or bike the player uses until the mission ends or this command is called again with 1.0, fDragMult range 1.0 - 15.0 (5.0 is standard for high air resistance zones on the map)
```
