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

## nActivityIsland Values:
| Value | Name |
| --- | --- |
| -1 | Invalid |
| 0 | General |
| 1 | Specific |
| 2 | Playlist |
| 3 | Event |
| 4 | Tournament |


## nContentCreator Values:
| Value | Name |
| --- | --- |
| 0 | Rockstar Created |
| 1 | User Created |

