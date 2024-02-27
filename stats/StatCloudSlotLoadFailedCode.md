---
ns: STATS
aliases: ["0xe496a53ba5f50a56"]
---
## STAT_CLOUD_SLOT_LOAD_FAILED_CODE

```c
// 0xE496A53BA5F50A56
int STAT_CLOUD_SLOT_LOAD_FAILED_CODE(int slot);
```

Returns LOAD failure code. Only returns a error if [`STAT_CLOUD_SLOT_LOAD_FAILED`](#_0x7F2C4CDF2E82DF4C)() return also TRUE.

## Return Type Values:
| Value | Name |
| --- | --- |
| 0 | None |
| 1 | Failed To Load |
| 2 | File Corrupt |
| 3 | Server Timeout |
| 4 | Server Error |
| 5 | File Not Found |
| 6 | Dirty Cloud Read |
| 7 | Dirty Profile Stat Read |
| 8 | Refresh Savemigration Status |

