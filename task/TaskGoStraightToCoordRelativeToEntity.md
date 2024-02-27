---
ns: TASK
aliases: ["0x61e360b7e040d12e"]
---
## TASK_GO_STRAIGHT_TO_COORD_RELATIVE_TO_ENTITY

```c
// 0x61E360B7E040D12E
void TASK_GO_STRAIGHT_TO_COORD_RELATIVE_TO_ENTITY(Ped ped, Entity entity, Vector3 Offset, float MoveBlendRatio, int Time);
```

Tells the ped to go to an offset coord from an entity, without using the navmesh.

if Time is chosen to be -1 the ped will never warp.


## Parameters
* **ped**: 
* **entity**: 
* **Offset**: 
* **MoveBlendRatio**: 
* **Time**: (Default value: `Default_Time_Before_Warp`)
