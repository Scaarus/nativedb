---
ns: NETWORK
aliases: ["0x13518ff1c6b28938"]
---
## NETWORK_CLAN_REQUEST_EMBLEM

```c
// 0x13518FF1C6B28938
bool NETWORK_CLAN_REQUEST_EMBLEM(int clanId);
```

Requests a crew emblem for a clan. Call this only once and make sure that you release it when done (NETWORK_CLAN_RELEASE_EMBLEM)


## Parameters
* **clanId**: the id of the clan
