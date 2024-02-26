---
ns: STATS
aliases: ["0xdeaaf77eb3687e97"]
---
## STAT_MIGRATE_CHECK_GET_PLATFORM_STATUS

```c
// 0xDEAAF77EB3687E97
int STAT_MIGRATE_CHECK_GET_PLATFORM_STATUS(Any* data);
```

Structure to retrieve available saves for migration.

## Return Type Values:
| Value | Name |
| --- | --- |
| 0 | None |
| 1 | Available |
| 2 | Running |
| 3 | Failed |
| 4 | Error Already Done |
| 5 | Error Not Available |

