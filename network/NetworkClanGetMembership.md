---
ns: NETWORK
aliases: ["0xc8bc2011f67b3411"]
---
## NETWORK_CLAN_GET_MEMBERSHIP

```c
// 0xC8BC2011F67B3411
bool NETWORK_CLAN_GET_MEMBERSHIP(gamer_handle gamerHandle, network_clan_desc memberInfo, int membershipIndex);
```

Get the membership description - you must call with NETWORK_CLAN_DOWNLOAD_MEMBERSHIP and NETWORK_CLAN_DOWNLOAD_MEMBERSHIP_PENDING.

