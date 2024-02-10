---
ns: NETWORK
aliases: ["0x4ba92a18502bca61"]
---
## NETWORK_START_RESPAWN_SEARCH_IN_ANGLED_AREA_FOR_PLAYER

```c
// 0x4BA92A18502BCA61
bool NETWORK_START_RESPAWN_SEARCH_IN_ANGLED_AREA_FOR_PLAYER(Player player, Vector3 vAngledAreaPos1, Vector3 vAngledAreaPos2, float fAngledAreaWidth, Vector3 vFaceTowardsPos, int iFlags);
```

This command initiates a search for spawn coordinates using the navmesh, using an angled area

## iFlags Values:
| Value | Name |
| --- | --- |
| 0 | Default |
| 2 | Ignore Target Heading |
| 4 | Prefer Close To Spawn Origin |
| 8 | May Spawn In Interior |
| 16 | May Spawn In Exterior |
| 32 | Prefer Wide Fov |
| 64 | Prefer Team Bunching |
| 128 | Prefer Enemy Players Farther |
| 256 | Prefer Friendly Players Closer |
| 512 | Prefer Enemy Ai Farther |
| 1024 | Prefer Friendly Ai Closer |
| 2048 | Prefer Randomness |


See 'NETWORK_START_RESPAWN_SEARCH_FOR_PLAYER' above

