---
ns: NETWORK
aliases: ["0xa091a5e44f0072e5"]
---
## NETWORK_DO_TRANSITION_QUICKMATCH_ASYNC

```c
// 0xA091A5E44F0072E5
bool NETWORK_DO_TRANSITION_QUICKMATCH_ASYNC(int nGameMode, int nMaxPlayers, int nActivityType, int nActivityID, int nMmFlags, int nActivityIsland);
```

## nActivityIsland Values:
| Value | Name |
| --- | --- |
| -1 | Invalid |
| 0 | General |
| 232 | Specific |
| 233 | Playlist |
| 234 | Event |
| 235 | Tournament |

