---
ns: NETWORK
aliases: ["0x5835d9cd92e83184"]
---
## NETWORK_CLAN_GET_EMBLEM_TXD_NAME

```c
// 0x5835D9CD92E83184
bool NETWORK_CLAN_GET_EMBLEM_TXD_NAME(Any* gamerHandle, Any* outTXDName);
```

Get the TXDtexture name of the giveh player's crew emblem.

!!!!READ THIS!!!! The crew emblem for a player can take time to download (a second or two), so if this returns false, but the player is in a valid crew, you may need to try again later. The crew emblem for each player is requested automatically when the player enters the session


## Parameters
* **gamerHandle**: of the gamer you want to get the emblem TXD name for
* **outTXDName**: the TXD AND texture name of the emblem (they are the same)
