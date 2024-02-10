---
ns: NETWORK
aliases: ["0x551ae6e8f7f29f4e"]
---
## NETWORK_SESSION_DO_FREEROAM_QUICKMATCH

```c
// 0x551AE6E8F7F29F4E
bool NETWORK_SESSION_DO_FREEROAM_QUICKMATCH(int gameMode, int maxPlayers, int matchmakingFlags);
```

Performs a quick match

## matchmakingFlags Values:
| Value | Name |
| --- | --- |
| 0 | S None |
| 212 |  Asynchronous |
| 213 |  Quickmatch |
| 214 |  Allow Blacklisted |
| 215 |  Disable Any Job Queries < Jobs Only |
| 216 |  Disable In Progress Queries < Jobs Only |
| 217 |  Rockstar Content Only < Jobs Only |
| 218 |  User Content Only < Jobs Only |
| 219 |  Is Boss |
| 220 |  Job To Job < To Game Only |
| 221 |  Bail From Launched Jobs < Jobs Only |
| 222 |  Only In Progress < Jobs Only |
| 223 |  To Game Via Transition < To Game Only |
| 224 |  Expanded Intro Flow |

