---
ns: NETWORK
aliases: ["0x71fb0ebcd4915d56"]
---
## NETWORK_DO_TRANSITION_QUICKMATCH

```c
// 0x71FB0EBCD4915D56
bool NETWORK_DO_TRANSITION_QUICKMATCH(int nGameMode, int nMaxPlayers, int nActivityType, int nActivityID, int nMmFlags, int nActivityIsland);
```

```
Find a transition session. If nActivityType is -1, we will find any open transition session (any activity) Otherwise, if nActivityID is 0, we will find any open transition of the type specified by nActivityType If matchmaking fails to find any results, we will host our own session if both nActivityType and nActivityID are valid.

Possible values for nActivityIsland:
| Index | Name |
| --- | --- |
| -1 | Invalid |
| 0 | General |
| 232 | Specific |
| 233 | Playlist |
| 234 | Event |
| 235 | Tournament |
```
