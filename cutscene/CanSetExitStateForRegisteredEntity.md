---
ns: CUTSCENE
aliases: ["0x4c6a6451c79e4662"]
---
## CAN_SET_EXIT_STATE_FOR_REGISTERED_ENTITY

```c
// 0x4C6A6451C79E4662
bool CAN_SET_EXIT_STATE_FOR_REGISTERED_ENTITY(string sSceneName, Hash modelHash);
```

Call this every frame to check if a peds state can be set for end of the cutscene.

Only need to pass the model in if the scene has both an IG_ and CS_ version of the same model, which will be swapped for a seamless exit ie the peds remain on screen at the end. Allows the entites state to be set in the final frame of the cutscene. Typically this will be for giving the ped a task that will match the final state of the cut scene. e.g. If the ped exits in cover in the cutscene then you can use SET_PED_DIRECTLY_INTO_COVER when this returns true so that peds new task matches the exit state of the scene.


## Parameters
* **sSceneName**: 
* **modelHash**: (Default value: `Dummy_Model_For_Script`)
