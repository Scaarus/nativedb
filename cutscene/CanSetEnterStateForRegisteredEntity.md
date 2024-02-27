---
ns: CUTSCENE
aliases: ["0x645d0b458d8e17b5"]
---
## CAN_SET_ENTER_STATE_FOR_REGISTERED_ENTITY

```c
// 0x645D0B458D8E17B5
bool CAN_SET_ENTER_STATE_FOR_REGISTERED_ENTITY(string sSceneName, Hash modelHash);
```

Call this to check if a peds state can be set for start of the cutscene.

Only need to pass the model in if the scene has both an IG_ and CS_ version of the same model


## Parameters
* **sSceneName**: 
* **modelHash**: (Default value: `Dummy_Model_For_Script`)
