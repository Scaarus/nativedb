---
ns: NETWORK
aliases: ["0x1f471b79acc90bef"]
---
## NETWORK_CLAN_GET_LOCAL_MEMBERSHIPS_COUNT

```c
// 0x1F471B79ACC90BEF
int NETWORK_CLAN_GET_LOCAL_MEMBERSHIPS_COUNT();
```

Get the CREW memberships count for the local gamer. (Number of crews we have) NOTE: Returns -1 if we're waiting for the server to respond with our count. It will assert if your don't have a valid Rockstar Id.

