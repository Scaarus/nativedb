---
ns: STATS
aliases: ["0x69dea3e9db727b4c"]
---
## PLAYSTATS_ODDJOB_DONE

```c
// 0x69DEA3E9DB727B4C
void PLAYSTATS_ODDJOB_DONE(int timeSpent, int oddJobId, int extraOddJobId);
```

Metric set when an oddjob is completed.


## Parameters
* **timeSpent**: Time spent in odd job.
* **oddJobId**: odd job
* **extraOddJobId**: default value is 0. Set only to distinguish different Locations of the mini-game. (Default value: `0`)
