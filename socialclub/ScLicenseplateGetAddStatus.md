---
ns: SOCIALCLUB
aliases: ["0x8147fff6a718e1ad"]
---
## SC_LICENSEPLATE_GET_ADD_STATUS

```c
// 0x8147FFF6A718E1AD
elicenseplate_add_status SC_LICENSEPLATE_GET_ADD_STATUS(int token);
```

get the current status of the string for this token
Use SC_LICENSEPLATE_GET_ADD_IS_PENDING() and wait for the request to finish.  Once it's finished, use SC_LICENSEPLATE_GET_ADD_STATUS() to get the status of the result.

## Return Type Values:
| Value | Name |
| --- | --- |
| -1 | Error |
| 37 | Ok |
| 38 | Pending |
| 39 | Invalid Token |

