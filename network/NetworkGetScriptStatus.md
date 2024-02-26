---
ns: NETWORK
aliases: ["0x57d158647a6bfabf"]
---
## NETWORK_GET_SCRIPT_STATUS

```c
// 0x57D158647A6BFABF
int NETWORK_GET_SCRIPT_STATUS();
```

You must wait for this to return NETSCRIPT_PLAYING before the script is allowed to continue. This is called before the broadcast variables are registered

## Return Type Values:
| Value | Name |
| --- | --- |
| 0 | Not Active |
| 1 | Joining |
| 2 | Playing |
| 3 | Terminated |
| 4 | Failed Session Full |
| 5 | Failed No Join In Progress |
| 6 | Failed Team Full |

