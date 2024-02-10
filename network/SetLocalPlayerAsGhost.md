---
ns: NETWORK
aliases: ["0x5ffe9b4144f9712f"]
---
## SET_LOCAL_PLAYER_AS_GHOST

```c
// 0x5FFE9B4144F9712F
void SET_LOCAL_PLAYER_AS_GHOST(bool Set, bool InvertGhosting);
```

Sets the local player as a ghost, so that other players are displayed semi-transparent and the local player will not be able to collide with them.

InvertGhosting is set to TRUE and bSet is TRUE, then the local player will be displayed semi-transparent instead (remote players will be rendered as normal)

