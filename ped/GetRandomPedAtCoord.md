---
ns: PED
aliases: ["0x876046a8e3a4b71c"]
---
## GET_RANDOM_PED_AT_COORD

```c
// 0x876046A8E3A4B71C
Ped GET_RANDOM_PED_AT_COORD(Vector3 CentrePosition, Vector3 LocateDimensions, int ExclusionPedType);
```

```
Gets a ped index in the given area.

Possible values for ExclusionPedType:
| Index | Name |
| --- | --- |
| -1 | Invalid |
| 0 | Player1 |
| 34 | Player2 Franklin |
| 35 | Player Network Player Controlled Over The Network (Not By This Machine) |
| 36 | Player Unused Trevor |
| 37 | Civmale |
| 38 | Civfemale |
| 39 | Cop |
| 40 | Gang1 |
| 41 | Gang2 |
| 42 | Gang3 |
| 43 | Gang4 |
| 44 | Gang5 |
| 45 | Gang6 |
| 46 | Gang7 |
| 47 | Gang8 |
| 48 | Gang9 |
| 49 | Gang10 |
| 50 | Gang Chinese Japanese |
| 51 | Gang Puerto Rican |
| 52 | Dealer |
| 53 | Medic |
| 54 | Fire |
| 55 | Criminal |
| 56 | Bum |
| 57 | Prostitute |
| 58 | Special |
| 59 | Mission |
| 60 | Swat |
| 61 | Animal |
| 62 | Army |
| 63 | Last Pedtype |
```
