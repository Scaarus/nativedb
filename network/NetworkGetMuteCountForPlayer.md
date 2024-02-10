---
ns: NETWORK
aliases: ["0xadb57e5b663cca8b"]
---
## NETWORK_GET_MUTE_COUNT_FOR_PLAYER

```c
// 0xADB57E5B663CCA8B
void NETWORK_GET_MUTE_COUNT_FOR_PLAYER(Player player, int outMuteCount, int outTalkerCount);
```

Get the mute count and number of talkers met for the given player


## Parameters
* **player**: 
* **outMuteCount**: number of times the given player has been muted by other players
* **outTalkerCount**: number of peole the player has met that could mute them (talkers)
