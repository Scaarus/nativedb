---
ns: PED
aliases: ["0x876046a8e3a4b71c"]
---
## GET_RANDOM_PED_AT_COORD

```c
// 0x876046A8E3A4B71C
Ped GET_RANDOM_PED_AT_COORD(Vector3 CentrePosition, Vector3 LocateDimensions, int ExclusionPedType);
```

Gets a ped index in the given area.

## ExclusionPedType Values:
| Value | Name |
| --- | --- |
| -1 | Invalid |
| 0 | Player1 |
| 1 | Player2 (Franklin) |
| 2 | Player Network (Player Controlled Over The Network (Not By This Machine)) |
| 3 | Player Unused (Trevor) |
| 4 | Civmale |
| 5 | Civfemale |
| 6 | Cop |
| 7 | Gang1 |
| 8 | Gang2 |
| 9 | Gang3 |
| 10 | Gang4 |
| 11 | Gang5 |
| 12 | Gang6 |
| 13 | Gang7 |
| 14 | Gang8 |
| 15 | Gang9 |
| 16 | Gang10 |
| 17 | Gang Chinese Japanese |
| 18 | Gang Puerto Rican |
| 19 | Dealer |
| 20 | Medic |
| 21 | Fire |
| 22 | Criminal |
| 23 | Bum |
| 24 | Prostitute |
| 25 | Special |
| 26 | Mission |
| 27 | Swat |
| 28 | Animal |
| 29 | Army |
| 30 | Last Pedtype |

