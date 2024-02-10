---
ns: STATS
aliases: ["0x8989cbd7b4e82534"]
---
## PLAYSTATS_MC_CLUBHOUSE_ACTIVITY

```c
// 0x8989CBD7B4E82534
void PLAYSTATS_MC_CLUBHOUSE_ACTIVITY(int bossId1, int bossId2, int matchId1, int matchId2, int minigameType, int jukeboxStation, int mcPointsEarned);
```

Telemetry sent whenever any of the actvity events finishes (Darts, Arm Wrestling, Drinking, Smoking, Jukebox) If not a jukebox activity, jukeboxStation should be set to -1

