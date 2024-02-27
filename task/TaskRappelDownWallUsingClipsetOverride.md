---
ns: TASK
aliases: ["0xeaf66acddc794793"]
---
## TASK_RAPPEL_DOWN_WALL_USING_CLIPSET_OVERRIDE

```c
// 0xEAF66ACDDC794793
void TASK_RAPPEL_DOWN_WALL_USING_CLIPSET_OVERRIDE(Ped ped, Vector3 StartPos, Vector3 RopeAnchorPos, float fDestinationHeight, Rope rope, string OverridenClipSet, bool SkipClimbOverWall);
```

To get AI or a player to rappel down the side of a wall or building, using the provided clipset

VecStartPos is the position that the ped should be in before playing the initial "climb over" animation ropeID is the ID of the rope that is being used for this rappel and the task fails without a valid ropeID fDestinationHeight is the Z position that is desired which the ped will not be allowed to go lower than VecRopeAnchorPos is the position that the rope is createdanchored at (the position that is likely passed into ADD_ROPE) OverridenClipSet is the clipset that will be used to override the rappel animations

This command handles rappelling down the side of a building given a specific rope and a desired height The specified ped will need to be in position prior to calling this task, otherwise heshe will be warped


## Parameters
* **ped**: 
* **StartPos**: 
* **RopeAnchorPos**: 
* **fDestinationHeight**: 
* **rope**: 
* **OverridenClipSet**: (Default value: `Null`)
* **SkipClimbOverWall**: (Default value: `False`)
