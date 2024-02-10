---
ns: NETWORK
aliases: ["0x7543bb439f63792b"]
---
## NETWORK_CLAN_IS_ROCKSTAR_CLAN

```c
// 0x7543BB439F63792B
bool NETWORK_CLAN_IS_ROCKSTAR_CLAN(network_clan_desc clanToCheck, int sizeOfData);
```

Determines if a given clan is a Rockstar clan or not (Isn't actually stored in the data we get back)
Requires that it's set up from NETWORK_CLAN_PLAYER_GET_DESC previously

