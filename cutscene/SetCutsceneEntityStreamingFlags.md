---
ns: CUTSCENE
aliases: ["0x4c61c75bee8184c2"]
---
## SET_CUTSCENE_ENTITY_STREAMING_FLAGS

```c
// 0x4C61C75BEE8184C2
void SET_CUTSCENE_ENTITY_STREAMING_FLAGS(string SceneHandle, Hash modelHash, int StreamingFlags);
```

Apply streaming related flags to entities.

## StreamingFlags Values:
| Value | Name |
| --- | --- |
| 0 | None |
| 1 | Dont Stream And Apply Variations |

