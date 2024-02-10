---
ns: STATS
aliases: ["0x7eec7e4f6984a16a"]
---
## LEADERBOARDS2_READ_BY_SCORE_INT

```c
// 0x7EEC7E4F6984A16A
bool LEADERBOARDS2_READ_BY_SCORE_INT(leaderboard2readdata in_lbData, int pivotScore, int numRows);
```

Reads leaderboard rows around a "pivot" score. The score is compared against the ranking column of the leaderboard.


## Parameters
* **in_lbData**: Leaderboard info for the read.
* **pivotScore**: score that is used as pivot to read MAX numRows.
* **numRows**: Total number of rows.
