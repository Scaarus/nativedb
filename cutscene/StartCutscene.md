---
ns: CUTSCENE
aliases: ["0x186d5cb5e7b0ff7b"]
---
## START_CUTSCENE

```c
// 0x186D5CB5E7B0FF7B
void START_CUTSCENE(int flags);
```

Starts a streamed cut scene.

## flags Values:
| Value | Name |
| --- | --- |
| 0 | No Options |
| 1 | Player Targetable |
| 2 | Procgrass Force Hd |
| 4 | Do Not Reposition Player To Scene Origin |
| 8 | No Widescreen Borders |
| 16 | Delay Enabling Player Control For Up To Date Gameplay Camera |
| 32 | Do Not Clear Pickups |
| 64 | Create Objects At Scene Origin |
| 128 | Player Exits In A Vehicle |
| 256 | Player Fp Flash Michael |
| 512 | Player Fp Flash Franklin |
| 1024 | Player Fp Flash Trevor |
| 2048 | Suppress Fp Transition Flash |
| 4096 | Use Fp Camera Blend Out Mode |
| 8192 | Exits Into Cover |

