---
ns: STATS
aliases: ["0xe662c8b759d08f3c"]
---
## LEADERBOARDS2_READ_BY_SCORE_FLOAT

```c
// 0xE662C8B759D08F3C
bool LEADERBOARDS2_READ_BY_SCORE_FLOAT(Any* in_lbData, float pivotScore, int numRows);
```

Reads leaderboard rows around a "pivot" score. The score is compared against the ranking column of the leaderboard.


## Parameters
* **in_lbData**: Leaderboard info for the read.
* **pivotScore**: score that is used as pivot to read MAX numRows.
* **numRows**: Total number of rows.
