---
ns: SAVEMIGRATION
aliases: ["0xc8cb5999919ea2ca"]
---
## SAVEMIGRATION_MP_GET_ACCOUNTS_STATUS

```c
// 0xC8CB5999919EA2CA
savemigration_status_codes SAVEMIGRATION_MP_GET_ACCOUNTS_STATUS();
```

Request the current status of the accounts request, if it returns SAVEMIGRATION_STATUS_OK the accounts request has compleded without error.

## Return Type Values:
| Value | Name |
| --- | --- |
| 0 | None |
| 1 | Ok |
| 2 | Pending |
| 3 | Inprogress |
| 4 | Canceled |
| 5 | Rolledback |
| 6 | Error |

