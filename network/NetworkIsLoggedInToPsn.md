---
ns: NETWORK
aliases: ["0xa0fa4ec6a05da44e"]
---
## NETWORK_IS_LOGGED_IN_TO_PSN

```c
// 0xA0FA4EC6A05DA44E
bool NETWORK_IS_LOGGED_IN_TO_PSN();
```

Returns TRUE if the main gamer index player is logged in to PSN. This does not guarantee the user is "online", i.e. their connection to PSN services could be down, they could be underage, etc. Use [NETWORK_IS_SIGNED_ONLINE](#_0x1077788E268557C2) for full online PSN connection.

