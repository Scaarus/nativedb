---
ns: SOCIALCLUB
aliases: ["0x930de22f07b1cce3"]
---
## SC_PROFANITY_GET_STRING_STATUS

```c
// 0x930DE22F07B1CCE3
int SC_PROFANITY_GET_STRING_STATUS(int token);
```

get the current status of the string for this token

Use [`SC_PROFANITY_GET_CHECK_IS_PENDING`](#_0x82E4A58BABC15AE7)() and wait for the request to finish. Once it's finished, use SC_PROFANITY_GET_STRING_STATUS() to get the status of the result.

## Return Type Values:
| Value | Name |
| --- | --- |
| -1 | Error |
| 0 | Ok |
| 1 | Failed |
| 2 | Pending |
| 3 | Invalid Token |

