---
ns: STREAMING
aliases: ["0x1f3f018bc3afa77c"]
---
## STREAMVOL_CREATE_FRUSTUM

```c
// 0x1F3F018BC3AFA77C
int STREAMVOL_CREATE_FRUSTUM(Vector3 pos, Vector3 dir, float farClip, int assetFlags, int lodFlags);
```

a streaming volume is a volume of the map which issues streaming requests for the specified assets, as a method for pre-streaming collisions or map data. this is an extremely expensive thing to do, so it is important to destroy the volume when no longer needed

## Values for `assetFlags`:
| Value | Name |
| --- | --- |
| 1 | Collisions Mover |
| 2 | Collisions Weapon |
| 12 | Mapdata |


## Values for `lodFlags`:
| Value | Name |
| --- | --- |
| 33 | High |
| 94 | Low |
| 127 | All |


assetFlags specifies what type of assets you want the volume to request and hold in memory. The majority of cases will only require map data and mover collision, specified as FLAG_COLLISIONS_MOVER | FLAG_MAPDATA

Creates a new frustum streaming volume for the specified asset types. Returns index of volume if successful, or -1 otherwise


## Parameters
* **pos**: 
* **dir**: 
* **farClip**: 
* **assetFlags**: 
* **lodFlags**: (Default value: `All`)
