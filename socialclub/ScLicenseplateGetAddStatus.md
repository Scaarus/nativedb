---
ns: SOCIALCLUB
aliases: ["0x8147fff6a718e1ad"]
---
## SC_LICENSEPLATE_GET_ADD_STATUS

```c
// 0x8147FFF6A718E1AD
int SC_LICENSEPLATE_GET_ADD_STATUS(int token);
```

get the current status of the string for this token

Use [SC_LICENSEPLATE_GET_ADD_IS_PENDING](#_0x07C61676E5BB52CD)() and wait for the request to finish. Once it's finished, use SC_LICENSEPLATE_GET_ADD_STATUS() to get the status of the result.

## Return Type Values:
| Value | Name |
| --- | --- |
| -1 | Error |
| 0 | Ok |
| 1 | Pending |
| 2 | Invalid Token |

