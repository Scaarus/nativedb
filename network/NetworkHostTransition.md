---
ns: NETWORK
aliases: ["0xa60bb5ce242bb254"]
---
## NETWORK_HOST_TRANSITION

```c
// 0xA60BB5CE242BB254
bool NETWORK_HOST_TRANSITION(int nGameMode, int nMaxPlayers, int nActivityType, int nActivityID, bool IsPrivate, bool IsOpen, bool FromMatchmaking, int nActivityIsland, int nContentCreator, int nHostFlags);
```

Host a transition session

## Values for `nActivityIsland`:
| Value | Name |
| --- | --- |
| -1 | Invalid |
| 0 | General |
| 1 | Specific |
| 2 | Playlist |
| 3 | Event |
| 4 | Tournament |


## Values for `nContentCreator`:
| Value | Name |
| --- | --- |
| 0 | Rockstar Created |
| 1 | User Created |


## Parameters
* **nGameMode**: 
* **nMaxPlayers**: 
* **nActivityType**: 
* **nActivityID**: 
* **IsPrivate**: 
* **IsOpen**: 
* **FromMatchmaking**: (Default value: `False`)
* **nActivityIsland**: (Default value: `General`)
* **nContentCreator**: (Default value: `Rockstar Created`)
* **nHostFlags**: (Default value: `0`)
