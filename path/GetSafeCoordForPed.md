---
ns: PATH
aliases: ["0xb61c8e878a4199ca"]
---
## GET_SAFE_COORD_FOR_PED

```c
// 0xB61C8E878A4199CA
bool GET_SAFE_COORD_FOR_PED(Vector3 Position, bool OnlyOnPavement, int iFlags);
```

Checks to see if it can find a safe bit of ground to place a ped. This command has been extended to provide a set of bitflags to give more control over how it searches for positions. (The old bOnlyOnPavement parameter still works but you should start using the GSC_FLAG_ONLY_PAVEMENT instead as it will be removed eventually.)

## iFlags Values:
| Value | Name |
| --- | --- |
| 0 | Default |
| 1 | Only Pavement |
| 2 | Not Isolated |
| 4 | Not Interior |
| 8 | Not Water |
| 16 | Only Network Spawn |
| 32 | Use Flood Fill |


If unsuccessful, the command will return FALSE and the returned coordinates will be the same as those passed in.

Use this carefully since it can have a considerable performance hit, having to stall the game whilst it queries navmesh polygons

