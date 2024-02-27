---
ns: CUTSCENE
aliases: ["0x1c9adda3244a1fbf"]
---
## START_CUTSCENE_AT_COORDS

```c
// 0x1C9ADDA3244A1FBF
void START_CUTSCENE_AT_COORDS(Vector3 vPos, int flags);
```

Starts a seamless cut scene at the given coords.

## Values for `flags`:
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


The given coords will act as the scene origin, round which all animations are authored.


## Parameters
* **vPos**: 
* **flags**: (Default value: `No Options`)
