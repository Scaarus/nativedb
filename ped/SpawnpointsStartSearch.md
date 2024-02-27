---
ns: PED
aliases: ["0x2df9038c90ad5264"]
---
## SPAWNPOINTS_START_SEARCH

```c
// 0x2DF9038C90AD5264
void SPAWNPOINTS_START_SEARCH(Vector3 vSearchOrigin, float fSearchRadius, float fMaxDistZ, int iFlags, float fMinimumSpacing, int iMaxSearchDurationMS);
```

Starts an asynchronous seach for spawnpoints Only a single search may be performed at any time; there is no queueing mechanism

## iFlags Values:
| Value | Name |
| --- | --- |
| 0 | Default |
| 1 | May Spawn In Interior |
| 2 | May Spawn In Exterior |
| 4 | Allow Not Network Spawn Candidate Polys |
| 8 | Allow Isolated Polys |
| 16 | Allow Road Polys |
| 32 | Only Points Against Edges |


vSearchOrigin, fSearchRadius and fMaxDistZ define an upright cylinder Optional 'fMinimumSpacing' specifies a minimum distance which must exist between returned points If optional 'iMaxSearchDurationMS' param is non-zero, search will enter a 'failed' state if this milliseconds duration is


## Parameters
* **vSearchOrigin**: 
* **fSearchRadius**: 
* **fMaxDistZ**: 
* **iFlags**: (Default value: `Default`)
* **fMinimumSpacing**: (Default value: `0`)
* **iMaxSearchDurationMS**: (Default value: `0`)
