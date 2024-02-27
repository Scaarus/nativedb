---
ns: NETWORK
aliases: ["0xa091a5e44f0072e5"]
---
## NETWORK_DO_TRANSITION_QUICKMATCH_ASYNC

```c
// 0xA091A5E44F0072E5
bool NETWORK_DO_TRANSITION_QUICKMATCH_ASYNC(int nGameMode, int nMaxPlayers, int nActivityType, int nActivityID, int nMmFlags, int nActivityIsland);
```

Find a transition session. If nActivityType is -1, we will find any open transition session (any activity) Otherwise, if nActivityID is 0, we will find any open transition of the type specified by nActivityType If matchmaking fails to find any results, we will host our own session if both nActivityType and nActivityID are valid.

## nActivityIsland Values:
| Value | Name |
| --- | --- |
| -1 | Invalid |
| 0 | General |
| 1 | Specific |
| 2 | Playlist |
| 3 | Event |
| 4 | Tournament |


## Parameters
* **nGameMode**: 
* **nMaxPlayers**: 
* **nActivityType**: 
* **nActivityID**: 
* **nMmFlags**: (Default value: `0`)
* **nActivityIsland**: (Default value: `Invalid`)
