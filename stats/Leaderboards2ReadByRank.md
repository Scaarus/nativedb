---
ns: STATS
aliases: ["0xba2c7db0c129449a"]
---
## LEADERBOARDS2_READ_BY_RANK

```c
// 0xBA2C7DB0C129449A
bool LEADERBOARDS2_READ_BY_RANK(Any* in_lbData, int rankStart, int numRows);
```

Start a read Operation by Rank.


## Parameters
* **in_lbData**: Leaderboard info for the read.
* **rankStart**: must be >= 1
* **numRows**: Total number of rows.
