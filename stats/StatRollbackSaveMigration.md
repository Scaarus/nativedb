---
ns: STATS
aliases: ["0xb3da2606774a8e2d"]
---
## STAT_ROLLBACK_SAVE_MIGRATION

```c
// 0xB3DA2606774A8E2D
bool STAT_ROLLBACK_SAVE_MIGRATION();
```

```
PURPOSE Must be called when the game needs to be rollback from a successfull migration. NOTES - Make sure the transaction id matches the SAVE_MIGRATION_TRANSACTION_ID otherwise it means the current state "RolledBack" was already dealt with. Local player must be online and the profile settings must be valid as well.
```
