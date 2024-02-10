---
ns: STATS
aliases: ["0x5ce587fb5a42c8c4"]
---
## LEADERBOARDS2_READ_BY_RADIUS

```c
// 0x5CE587FB5A42C8C4
bool LEADERBOARDS2_READ_BY_RADIUS(leaderboard2readdata in_lbData, int radius, gamer_handle pivotGamerHandle);
```

Start a read Operation by Radius.


## Parameters
* **in_lbData**: Leaderboard info for the read.
* **radius**: must be >= 1
* **pivotGamerHandle**: Gamer Handle of the player being used as pivot.
