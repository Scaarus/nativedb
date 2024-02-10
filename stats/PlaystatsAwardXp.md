---
ns: STATS
aliases: ["0x46f917f6b4128fe4"]
---
## PLAYSTATS_AWARD_XP

```c
// 0x46F917F6B4128FE4
void PLAYSTATS_AWARD_XP(int amount, int type, int category);
```

```
Tells the PlayStats that the player won XP
```

## Parameters
* **amount**: amount of xp
* **type**: string hash of the xp type < actual XP reason >
* **category**: string hash of the xp category < the bucket it goes into (e.g. if its an award, even though there are many individual award sources) >
