---
ns: PLAYER
aliases: ["0x75e7d505f2b15902"]
---
## SET_PLAYER_FORCED_ZOOM

```c
// 0x75E7D505F2B15902
void SET_PLAYER_FORCED_ZOOM(Player player, bool ForcedZoom);
```

```
Forces the player to be zoomed in by default when aiming

This flag gets reset each frame, so should be called each frame while you want this behaviour
```
