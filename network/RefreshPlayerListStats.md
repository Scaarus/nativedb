---
ns: NETWORK
aliases: ["0xe26ccff8094d8c74"]
---
## REFRESH_PLAYER_LIST_STATS

```c
// 0xE26CCFF8094D8C74
bool REFRESH_PLAYER_LIST_STATS(int type);
```

Checks for when the playerlist changes, and triggers for the new stats to be grabbed. Returns true when the Player List is up to date.

## type Values:
| Value | Name |
| --- | --- |
| 0 | Joined |
| 1 | Corona Players |
| 2 | Invitable Session Players |
| 3 | Matched Players |
| 4 | Corona Playlist |
| 5 | Directory |
| 100 | Last Job |

