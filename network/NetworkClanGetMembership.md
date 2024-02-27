---
ns: NETWORK
aliases: ["0xc8bc2011f67b3411"]
---
## NETWORK_CLAN_GET_MEMBERSHIP

```c
// 0xC8BC2011F67B3411
bool NETWORK_CLAN_GET_MEMBERSHIP(Any* gamerHandle, Any* memberInfo, int membershipIndex);
```

Get the membership description - you must call with [`NETWORK_CLAN_DOWNLOAD_MEMBERSHIP`](#_0xA989044E70010ABE) and [`NETWORK_CLAN_DOWNLOAD_MEMBERSHIP_PENDING`](#_0x5B9E023DC6EBEDC0).

