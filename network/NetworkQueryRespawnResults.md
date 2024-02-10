---
ns: NETWORK
aliases: ["0x3c891a251567dfce"]
---
## NETWORK_QUERY_RESPAWN_RESULTS

```c
// 0x3C891A251567DFCE
respawn_query_results NETWORK_QUERY_RESPAWN_RESULTS();
```

This command queries progress & retrieves spawn coordinates

## Return Type Values:
| Value | Name |
| --- | --- |
| 0 | Failed |
| 1 | Succeeded |
| 2 | Still Working |
| 3 | No Search Active |

Return value is one of the RESPAWN_QUERY_RESULTS enumerated type vOutSpawnPos,

