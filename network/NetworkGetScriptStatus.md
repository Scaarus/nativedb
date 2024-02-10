---
ns: NETWORK
aliases: ["0x57d158647a6bfabf"]
---
## NETWORK_GET_SCRIPT_STATUS

```c
// 0x57D158647A6BFABF
network_script_state NETWORK_GET_SCRIPT_STATUS();
```

You must wait for this to return NETSCRIPT_PLAYING before the script is allowed to continue. This is called before the broadcast variables are registered

## Return Type Values:
| Value | Name |
| --- | --- |
| 27 | Not Active |
| 28 | Joining |
| 29 | Playing |
| 30 | Terminated |
| 31 | Failed Session Full |
| 32 | Failed No Join In Progress |
| 33 | Failed Team Full |

