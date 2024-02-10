---
ns: STREAMING
aliases: ["0x0ad9710cee2f590f"]
---
## STREAMVOL_CREATE_LINE

```c
// 0x0AD9710CEE2F590F
int STREAMVOL_CREATE_LINE(Vector3 pos1, Vector3 pos2, int assetFlags);
```

a streaming volume is a volume of the map which issues streaming requests for the specified assets, as a method for pre-streaming collisions or map data. this is an extremely expensive thing to do, so it is important to destroy the volume when no longer needed

## assetFlags Values:
| Value | Name |
| --- | --- |
| 1 | Collisions Mover |
| 2 | Collisions Weapon |
| 12 | Mapdata |


currently the only asset supported is FLAG_COLLISIONS_MOVER

Creates a new line-segment streaming volume for the specified asset types. Returns index of volume if successful, or -1 otherwise

