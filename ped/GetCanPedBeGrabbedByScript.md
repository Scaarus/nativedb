---
ns: PED
aliases: ["0x03ea03af85a85cb7"]
---
## GET_CAN_PED_BE_GRABBED_BY_SCRIPT

```c
// 0x03EA03AF85A85CB7
bool GET_CAN_PED_BE_GRABBED_BY_SCRIPT(Ped ped, bool ScanRandomPeds, bool ScanMissionPeds, bool CheckIfThePedIsInAGroup, bool CheckIfThePedIsInAVehicle, bool CheckPlayerPeds, bool ReturnDeadOrDyingPeds, bool ReturnPedsWithScriptedTasks, int ExclusionPedType);
```

```
Returns whether a given ped meets the given criteria to become script controlled

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
