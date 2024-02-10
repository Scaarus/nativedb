---
ns: SAVEMIGRATION
aliases: ["0x690b76bd2763e068"]
---
## SAVEMIGRATION_MP_GET_STATUS

```c
// 0x690B76BD2763E068
savemigration_status_codes SAVEMIGRATION_MP_GET_STATUS();
```

Get the current status of the users save migration, if it returns SAVEMIGRATION_STATUS_OK if the user can enter a multiplayer session.

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

