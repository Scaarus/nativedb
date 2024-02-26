---
ns: NETWORK
aliases: ["0x8e02d73914064223"]
---
## NETWORK_ADD_FRIEND

```c
// 0x8E02D73914064223
bool NETWORK_ADD_FRIEND(Any* gamerHandle, string message);
```

Sends an invitation to a player to become your friend. On PS3, opens add friend dialogue with message On 360, opens friend request UI (no message) On PC, sends social club invite Check [NETWORK_IS_ADDING_FRIEND](#_0x6EA101606F6E4D81) returns FALSE - we cannot have concurrent requests

