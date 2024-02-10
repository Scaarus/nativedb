---
ns: STATS
aliases: ["0xbc80e22ded931e3d"]
---
## PLAYSTATS_MATCH_STARTED

```c
// 0xBC80E22DED931E3D
void PLAYSTATS_MATCH_STARTED(string matchCreator, string uniqueMatchId, matchstartinfo info);
```

Tells the PlayStats that a match has started. The host needs to call PLAYSTATS_CREATE_MATCH_HISTORY_ID and share the values of matchHistoryIdA & matchHistoryIdB among all match participants.

