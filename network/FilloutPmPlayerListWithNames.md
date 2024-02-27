---
ns: NETWORK
aliases: ["0x716b6db9d1886106"]
---
## FILLOUT_PM_PLAYER_LIST_WITH_NAMES

```c
// 0x716B6DB9D1886106
bool FILLOUT_PM_PLAYER_LIST_WITH_NAMES(Any* gamerHandles, Any* gamerNames, int count, int type);
```

Fills out the list of players in the PM Player List (clears the previous data).

## Values for `type`:
| Value | Name |
| --- | --- |
| 0 | Joined |
| 1 | Corona Players |
| 2 | Invitable Session Players |
| 3 | Matched Players |
| 4 | Corona Playlist |
| 5 | Directory |
| 100 | Last Job |


## Parameters
* **gamerHandles**: 
* **gamerNames**: 
* **count**: 
* **type**: (Default value: `Corona Players`)
