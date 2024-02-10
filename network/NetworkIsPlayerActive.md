---
ns: NETWORK
aliases: ["0xb8dfd30d6973e135"]
---
## NETWORK_IS_PLAYER_ACTIVE

```c
// 0xB8DFD30D6973E135
bool NETWORK_IS_PLAYER_ACTIVE(Player player);
```

Returns true if the given player is active (this adds check that the player ped is created vs. NETWORK_IS_PLAYER_CONNECTED)

