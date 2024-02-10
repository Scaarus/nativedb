---
ns: NETWORK
aliases: ["0x7808619f31ff22db"]
---
## NETWORK_IS_CONNETED_TO_NP_PRESENCE

```c
// 0x7808619F31FF22DB
bool NETWORK_IS_CONNETED_TO_NP_PRESENCE();
```

```
Returns TRUE if the player is connected to either PSN or R* Presence When FALSE, we can safely assume an internet connection has been lost. Use this when handling connection change events to determine if the user has gone offline due to a sign out or net connection loss.
```
