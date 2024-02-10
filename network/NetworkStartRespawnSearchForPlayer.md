---
ns: NETWORK
aliases: ["0x5a6ffa2433e2f14c"]
---
## NETWORK_START_RESPAWN_SEARCH_FOR_PLAYER

```c
// 0x5A6FFA2433E2F14C
bool NETWORK_START_RESPAWN_SEARCH_FOR_PLAYER(Player player, Vector3 vSearchPos, float fSearchRadius, Vector3 vFaceTowardsPos, int iFlags);
```

This command initiates a search for spawn coordinates using the navmesh, using a spherical volume

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


## Parameters
* **player**: 
* **vSearchPos**: the location where you wish to find a spawn coordinate
* **fSearchRadius**: the range of the search
* **vFaceTowardsPos**: the position which you wish the spawn coordinate to face towards
* **iFlags**: optional flags
