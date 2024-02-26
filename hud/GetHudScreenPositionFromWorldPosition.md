---
ns: HUD
aliases: ["0xf9904d11f1acbec3"]
---
## GET_HUD_SCREEN_POSITION_FROM_WORLD_POSITION

```c
// 0xF9904D11F1ACBEC3
int GET_HUD_SCREEN_POSITION_FROM_WORLD_POSITION(Vector3 vWorldPos, float fScreenPosX, float fScreenPosY);
```

converts a world position to a position on screen for the HUD and returns direction off screen

## Return Type Values:
| Value | Name |
| --- | --- |
| 0 | East |
| 1 | North |
| 2 | South |
| 3 | West |

