---
ns: NETWORK
aliases: ["0xa134777ff7f33331"]
---
## NETWORK_CLAN_IS_EMBLEM_READY

```c
// 0xA134777FF7F33331
bool NETWORK_CLAN_IS_EMBLEM_READY(int clanId, Any* outTXDName);
```

Returns true when a requested clan emblem (via [NETWORK_CLAN_REQUEST_EMBLEM](#_0x13518FF1C6B28938)) is loaded


## Parameters
* **clanId**: the id of the clan
* **outTXDName**: the TXD AND texture name of the emblem (they are the same)
