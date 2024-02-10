---
ns: SOCIALCLUB
aliases: ["0x5c4ebffa98bdb41c"]
---
## SC_LICENSEPLATE_GET_ISVALID_STATUS

```c
// 0x5C4EBFFA98BDB41C
elicenseplate_isvalid_status SC_LICENSEPLATE_GET_ISVALID_STATUS(int token);
```

get the current status of the string for this token
Use SC_LICENSEPLATE_GET_ISVALID_IS_PENDING() and wait for the request to finish.  Once it's finished, use SC_LICENSEPLATE_GET_ISVALID_STATUS() to get the status of the result.

## Return Type Values:
| Value | Name |
| --- | --- |
| -1 | Error |
| 42 | Ok |
| 43 | Pending |
| 44 | Profane |
| 45 | Reserved |
| 46 | Malformed |
| 47 | Notvalid |
| 48 | Invalid Token |

