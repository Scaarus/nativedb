---
ns: NETWORK
aliases: ["0xbb6e6fee99d866b2"]
---
## NETWORK_CLAN_REMOTE_MEMBERSHIPS_ARE_IN_CACHE

```c
// 0xBB6E6FEE99D866B2
bool NETWORK_CLAN_REMOTE_MEMBERSHIPS_ARE_IN_CACHE();
```

Code always remembers the last remote player's downloaded memberships retreived using NETWORK_CLAN_DOWNLOAD_MEMBERSHIP. Script can use this func to check if data is there, and avoid calling NETWORK_CLAN_DOWNLOAD_MEMBERSHIP if we don't need to force a refresh

