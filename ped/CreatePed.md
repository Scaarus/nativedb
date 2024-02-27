---
ns: PED
aliases: ["0xd49f9b0955c367de"]
---
## CREATE_PED

```c
// 0xD49F9B0955C367DE
Ped CREATE_PED(int PedType, Hash modelHash, Vector3 NewPosition, float fPedHeading, bool RegisterAsNetworkObject, bool ScriptHostObject);
```

Creates a ped on foot at the specified co-ordinates with heading.

these are for the old style, depricated Ped Blood damage functions, and will go away. Checks which peds can be created These should match the PropTypes enum in PedProps.h They are used by RESTRICT_PED_PROPS FA: !!!DEPRECATED!!! Keep in sync with eAnimEvents in AnimFlags.h must match order in commands_ped.cpp Keep this in sync with enum BehaviourFlags in CombatData.h states that will for motion update Defaults are taken from gta5\build\dev\common\data\ai\combatbehaviour.meta

## PedType Values:
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


PED_TYPE is contained in command_ped.


## Parameters
* **PedType**: 
* **modelHash**: 
* **NewPosition**: 
* **fPedHeading**: (Default value: `0`)
* **RegisterAsNetworkObject**: The new object will be created and synced on other machines if a network game is running (Default value: `True`)
* **ScriptHostObject**: If true, this object has been created by the host portion of a network script and is vital to that (Default value: `True`)
