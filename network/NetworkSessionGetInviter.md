---
ns: NETWORK
aliases: ["0xe57397b4a3429dd0"]
---
## NETWORK_SESSION_GET_INVITER

```c
// 0xE57397B4A3429DD0
void NETWORK_SESSION_GET_INVITER(Any* gamerHandle);
```

Fills in gamer handle of player who invited us to this session. This asserts if [`NETWORK_SESSION_WAS_INVITED`](#_0x23DFB504655D0CE4) is FALSE

