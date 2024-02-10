---
ns: NETWORK
aliases: ["0x6ea101606f6e4d81"]
---
## NETWORK_IS_ADDING_FRIEND

```c
// 0x6EA101606F6E4D81
bool NETWORK_IS_ADDING_FRIEND();
```

```
Sends an invitation to a player to become your friend. Only available on PS3 - calling on other platforms will ASSERT A return value of false means that we're still processing the last friend request Wait until it returns true (indicating success)
```
