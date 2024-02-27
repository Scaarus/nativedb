---
ns: SOCIALCLUB
aliases: ["0x16da8172459434aa"]
---
## SC_EMAIL_GET_RETRIEVAL_STATUS

```c
// 0x16DA8172459434AA
int SC_EMAIL_GET_RETRIEVAL_STATUS();
```

Returns the retrieval status after [`SC_EMAIL_RETRIEVE_EMAILS`](#_0x040ADDCBAFA1018A) has been called

## Return Type Values:
| Value | Name |
| --- | --- |
| 0 | None |
| 1 | Pending |
| 2 | Failed |
| 3 | Succeeded |
| 4 | Cancelled |

