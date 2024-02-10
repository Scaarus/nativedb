---
ns: STREAMING
aliases: ["0x219c7b8d53e429fd"]
---
## STREAMVOL_CREATE_SPHERE

```c
// 0x219C7B8D53E429FD
int STREAMVOL_CREATE_SPHERE(Vector3 pos, float radius, int assetFlags, int lodFlags);
```

```
a streaming volume is a volume of the map which issues streaming requests for the specified assets, as a method for pre-streaming collisions or map data. this is an extremely expensive thing to do, so it is important to destroy the volume when no longer needed

Possible values for assetFlags:
| Index | Name |
| --- | --- |
| 1 | Collisions Mover |
| 2 | Collisions Weapon |
| 12 | Mapdata |


Possible values for lodFlags:
| Index | Name |
| --- | --- |
| 33 | High |
| 94 | Low |
| 127 | All |


assetFlags specifies what type of assets you want the volume to request and hold in memory. The majority of cases will only require map data and mover collision, specified as FLAG_COLLISIONS_MOVER | FLAG_MAPDATA

Creates a new spherical streaming volume for the specified asset types. Returns index of volume if successful, or -1 otherwise
```
