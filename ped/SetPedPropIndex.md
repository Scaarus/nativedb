---
ns: PED
aliases: ["0x93376b65a266eb5f"]
---
## SET_PED_PROP_INDEX

```c
// 0x93376B65A266EB5F
void SET_PED_PROP_INDEX(int Position, int NewPropIndex, int NewTextIndex, bool SyncWithBlend);
```

Set the id of the prop at the given position for the given ped.

## Position Values:
| Value | Name |
| --- | --- |
| 0 | Head |
| 1 | Eyes |
| 2 | Ears |
| 3 | Mouth |
| 4 | Left Hand |
| 5 | Right Hand |
| 6 | Left Wrist |
| 7 | Right Wrist |
| 8 | Hip |


PED_PROP_POSITION in commands_ped.sch


## Parameters
* **Position**: 
* **NewPropIndex**: 
* **NewTextIndex**: (Default value: `0`)
* **SyncWithBlend**: (Default value: `False`)
