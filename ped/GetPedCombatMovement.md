---
ns: PED
aliases: ["0xdea92412fcaeb3f5"]
---
## GET_PED_COMBAT_MOVEMENT

```c
// 0xDEA92412FCAEB3F5
int GET_PED_COMBAT_MOVEMENT(Ped ped);
```

Get the current type of combat movement

## Return Type Values:
| Value | Name |
| --- | --- |
| 0 | Stationary (Stands Totally Still During Combat) |
| 1 | Defensive (Seeks A Defensive Position.) |
| 2 | Willadvance (Will Advance Forward In Combat) |
| 3 | Willretreat (Will Retreat If The Enemy Gets Too Close) |

