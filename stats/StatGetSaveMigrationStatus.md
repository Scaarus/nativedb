---
ns: STATS
aliases: ["0x886913bbeaca68c1"]
---
## STAT_GET_SAVE_MIGRATION_STATUS

```c
// 0x886913BBEACA68C1
save_migration_status STAT_GET_SAVE_MIGRATION_STATUS();
```

Structure to retrieve available saves for migration. PURPOSE Check the status of STAT_SAVE_MIGRATION_STATUS_START(). We need to call this 1st to make sure the game is not returning SMS_SKIP_ACCOUNT_ALREADY_USED which means we dont need to call STAT_SAVE_MIGRATION_STATUS_START( ). Also the tunable check to skip STAT_SAVE_MIGRATION_STATUS_START( ) must be added at this point. NOTES You must have this before using this command - ARE_PROFILE_SETTINGS_VALID( ) and NETWORK_IS_SIGNED_ONLINE()

## Return Type Values:
| Value | Name |
| --- | --- |
| 64 | None |
| 65 | Failed |
| 66 | Canceled |
| 67 | Succedded |
| 68 | Pending |
| 69 | Skip Account Already Used |
| 70 | Skip Invalid Status |

