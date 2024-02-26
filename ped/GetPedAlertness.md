---
ns: PED
aliases: ["0xf6aa118530443fd2"]
---
## GET_PED_ALERTNESS

```c
// 0xF6AA118530443FD2
int GET_PED_ALERTNESS(Ped ped);
```

Gets a peds alertness state (returns -1 if invalid)

## Return Type Values:
| Value | Name |
| --- | --- |
| 0 | Not Alert |
| 1 | Alert |
| 2 | Very Alert |
| 3 | Must Go To Combat |

