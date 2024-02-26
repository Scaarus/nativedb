---
ns: NETWORK
aliases: ["0x74fb3e29e6d10fa9"]
---
## NETWORK_GET_NP_UNAVAILABLE_REASON

```c
// 0x74FB3E29E6D10FA9
int NETWORK_GET_NP_UNAVAILABLE_REASON();
```

Returns the reason why the NP service is unavailable. Will return REASON_INVALID if this function is called when Np is available and will assert

## Return Type Values:
| Value | Name |
| --- | --- |
| -1 | Invalid |
| 0 | Other |
| 1 | System Update |
| 2 | Game Update |
| 3 | Signed Out |
| 4 | Age |
| 5 | Connection |

