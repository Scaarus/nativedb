---
ns: CUTSCENE
aliases: ["0x2a56c06ebef2b0d9"]
---
## SET_CUTSCENE_PED_COMPONENT_VARIATION_FROM_PED

```c
// 0x2A56C06EBEF2B0D9
void SET_CUTSCENE_PED_COMPONENT_VARIATION_FROM_PED(string SceneHandle, Ped ped, Hash modelHash);
```

Requests the variations from one ped to be streamed and applied to the cutscene version.

Always apply this to the CS version, all cs variations will be copied to the ig version, if one is present. Use [`CAN_REQUEST_ASSETS_FOR_CUTSCENE_ENTITY`](#_0xB56BBBCC2955D9CB) to be sure that the variation request has been made as this command only returns true FOR A SINGLE FRAME.


## Parameters
* **SceneHandle**: 
* **ped**: 
* **modelHash**: (Default value: `Dummy_Model_For_Script`)
