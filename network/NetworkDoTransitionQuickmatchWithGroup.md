---
ns: NETWORK
aliases: ["0x9c4ab58491fdc98a"]
---
## NETWORK_DO_TRANSITION_QUICKMATCH_WITH_GROUP

```c
// 0x9C4AB58491FDC98A
bool NETWORK_DO_TRANSITION_QUICKMATCH_WITH_GROUP(int nGameMode, int nMaxPlayers, int nActivityType, int nActivityID, Any* hGamers, int nNumGamers, int nMmFlags, int nActivityIsland);
```

Find a transition session. Variant of above that works with a group

## nActivityIsland Values:
| Value | Name |
| --- | --- |
| -1 | Invalid |
| 0 | General |
| 1 | Specific |
| 2 | Playlist |
| 3 | Event |
| 4 | Tournament |

