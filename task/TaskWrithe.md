---
ns: TASK
aliases: ["0xcddc2b77ce54ac6e"]
---
## TASK_WRITHE

```c
// 0xCDDC2B77CE54AC6E
void TASK_WRITHE(Ped ped, Ped ped, int nMinFireLoops, int StartState, bool ForceShootOnGround, int nShootFromGroundTimer);
```

Puts the ped into the hurt state, a target needs to be provided

## StartState Values:
| Value | Name |
| --- | --- |
| 0 | Shm Onground |


MinFireLoops is atleast how many times the ped will be going in the shoot from ground


## Parameters
* **ped**: 
* **ped**: 
* **nMinFireLoops**: 
* **StartState**: (Default value: `Shm Onground`)
* **ForceShootOnGround**: Makes the ped go into the shooting from ground state, and prevents him from randomly dying in the loops (Default value: `False`)
* **nShootFromGroundTimer**: Time in milliseconds that defines how long ped keeps shooting in each cycle (before playing writhe anims again)
