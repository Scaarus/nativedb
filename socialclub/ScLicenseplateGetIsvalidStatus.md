---
ns: SOCIALCLUB
aliases: ["0x5c4ebffa98bdb41c"]
---
## SC_LICENSEPLATE_GET_ISVALID_STATUS

```c
// 0x5C4EBFFA98BDB41C
int SC_LICENSEPLATE_GET_ISVALID_STATUS(int token);
```

get the current status of the string for this token

Use [SC_LICENSEPLATE_GET_ISVALID_IS_PENDING](#_0xD302E99EDF0449CF)() and wait for the request to finish. Once it's finished, use SC_LICENSEPLATE_GET_ISVALID_STATUS() to get the status of the result.

## Return Type Values:
| Value | Name |
| --- | --- |
| -1 | Error |
| 0 | Ok |
| 1 | Pending |
| 2 | Profane |
| 3 | Reserved |
| 4 | Malformed |
| 5 | Notvalid |
| 6 | Invalid Token |

