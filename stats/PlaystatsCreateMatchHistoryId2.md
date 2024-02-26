---
ns: STATS
aliases: ["0x6dee77aff8c21bd1"]
---
## PLAYSTATS_CREATE_MATCH_HISTORY_ID_2

```c
// 0x6DEE77AFF8C21BD1
bool PLAYSTATS_CREATE_MATCH_HISTORY_ID_2(int hashedMac, int posixTime);
```

Call this to create a match history ID to be shared among all machines participating in the match. The host should call this and share both int's in the broadcast data.

