---
ns: STATS
aliases: ["0x4fef53183c3c6414"]
---
## STAT_SAVE_MIGRATION_CANCEL_PENDING_OPERATION

```c
// 0x4FEF53183C3C6414
bool STAT_SAVE_MIGRATION_CANCEL_PENDING_OPERATION();
```

```
PURPOSE Cancel a save migration that has pending for too long. This can only be done after STAT_GET_SAVE_MIGRATION_STATUS is SMS_SUCCEDDED because I will be checking that data. NOTES - Call STAT_SAVE_MIGRATION_STATUS_START and make sure is succedds. - Check the pending Migration in progress.
```
