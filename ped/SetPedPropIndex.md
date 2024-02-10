---
ns: PED
aliases: ["0x93376b65a266eb5f"]
---
## SET_PED_PROP_INDEX

```c
// 0x93376B65A266EB5F
void SET_PED_PROP_INDEX(int Position, int NewPropIndex, int NewTextIndex, bool SyncWithBlend);
```

```
Set the id of the prop at the given position for the given ped.

Possible values for Position:
| Index | Name |
| --- | --- |
| 0 | Head |
| 131 | Eyes |
| 132 | Ears |
| 133 | Mouth |
| 134 | Left Hand |
| 135 | Right Hand |
| 136 | Left Wrist |
| 137 | Right Wrist |
| 138 | Hip |


PED_PROP_POSITION in commands_ped.sch
```
