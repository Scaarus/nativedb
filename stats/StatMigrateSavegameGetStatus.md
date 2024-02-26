---
ns: STATS
aliases: ["0x9a62ec95ae10e011"]
---
## STAT_MIGRATE_SAVEGAME_GET_STATUS

```c
// 0x9A62EC95AE10E011
int STAT_MIGRATE_SAVEGAME_GET_STATUS();
```

Migrate savegames from previous generation console.

## Return Type Values:
| Value | Name |
| --- | --- |
| 0 | None |
| 1 | Failed Source In Use |
| 2 | Failed Already Done |
| 3 | Failed In Progress |
| 4 | Failed Unlock Already Used |
| 5 | Failed Insufficient Privileges |
| 6 | Failed Cheater |
| 7 | Failed Banned |
| 8 | Failed Maintenance |
| 9 | Failed Acct Creation Date |
| 10 | Failed Acct Age |
| 11 | Error Dest Already Done |
| 12 | Error Too Rich |

