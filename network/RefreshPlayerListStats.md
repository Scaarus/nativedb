---
ns: NETWORK
aliases: ["0xe26ccff8094d8c74"]
---
## REFRESH_PLAYER_LIST_STATS

```c
// 0xE26CCFF8094D8C74
bool REFRESH_PLAYER_LIST_STATS(int type);
```

```
Checks for when the playerlist changes, and triggers for the new stats to be grabbed. Returns true when the Player List is up to date.

Possible values for type:
| Index | Name |
| --- | --- |
| 100 | Last Job |
| 250 | Joined |
| 251 | Corona Players |
| 252 | Invitable Session Players |
| 253 | Matched Players |
| 254 | Corona Playlist |
| 255 | Directory |
```
