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

## PedType Values:
| Value | Name |
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


PED_TYPE is contained in command_ped.


## Parameters
* **PedType**: 
* **modelHash**: 
* **NewPosition**: 
* **fPedHeading**: 
* **RegisterAsNetworkObject**: The new object will be created and synced on other machines if a network game is running
* **ScriptHostObject**: If true, this object has been created by the host portion of a network script and is vital to that
