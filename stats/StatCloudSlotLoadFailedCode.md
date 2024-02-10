---
ns: STATS
aliases: ["0xe496a53ba5f50a56"]
---
## STAT_CLOUD_SLOT_LOAD_FAILED_CODE

```c
// 0xE496A53BA5F50A56
cloud_load_failure_codes STAT_CLOUD_SLOT_LOAD_FAILED_CODE(int slot);
```

Returns LOAD failure code. Only returns a error if STAT_CLOUD_SLOT_LOAD_FAILED() return also TRUE.

## Return Type Values:
| Value | Name |
| --- | --- |
| 27 | None |
| 28 | Failed To Load |
| 29 | File Corrupt |
| 30 | Server Timeout |
| 31 | Server Error |
| 32 | File Not Found |
| 33 | Dirty Cloud Read |
| 34 | Dirty Profile Stat Read |
| 35 | Refresh Savemigration Status |
| 36 | Max |

