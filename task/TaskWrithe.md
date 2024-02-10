---
ns: TASK
aliases: ["0xcddc2b77ce54ac6e"]
---
## TASK_WRITHE

```c
// 0xCDDC2B77CE54AC6E
void TASK_WRITHE(Ped ped, Ped ped, int nMinFireLoops, int StartState, bool ForceShootOnGround, int nShootFromGroundTimer);
```

```
Puts the ped into the hurt state, a target needs to be provided

Possible values for StartState:
| Index | Name |
| --- | --- |
| 0 |  |


MinFireLoops is atleast how many times the ped will be going in the shoot from ground
```

## Parameters
* **ped**: 
* **ped**: 
* **nMinFireLoops**: 
* **StartState**: 
* **ForceShootOnGround**: Makes the ped go into the shooting from ground state, and prevents him from randomly dying in the loops
* **nShootFromGroundTimer**: Time in milliseconds that defines how long ped keeps shooting in each cycle (before playing writhe anims again)
