---
ns: PED
aliases: ["0xf28965d04f570dca"]
---
## FORCE_PED_MOTION_STATE

```c
// 0xF28965D04F570DCA
bool FORCE_PED_MOTION_STATE(Ped ped, int state, int exitstate, bool ForceAIPreCameraUpdate);
```

```
Forces the peds motion state next frame to the provided known state.

Possible values for state:
| Index | Name |
| --- | --- |
| -1871534317 | On Foot Idle |
| -1855028596 | Diving Swim |
| -1161760501 | Parachuting |
| -1115154469 | On Foot Sprint |
| -762290521 | Actionmode Walk |
| -668482597 | On Foot Walk |
| -633298724 | Actionmode Idle |
| -83133983 | Stealthmode Run |
| -530524 | On Foot Run |
| 69908130 | Stealthmode Walk |
| 147004056 | Crouch Walk |
| 247561816 | Do Nothing |
| 834330132 | Actionmode Run |
| 898879241 | Crouch Run |
| 1063765679 | Aiming |
| 1110276645 | Stealthmode Idle |
| 1140525470 | Crouch Idle |
| 1212730861 | Diving Idle |


Possible values for exitstate:
| Index | Name |
| --- | --- |
| 0 | Default |
| 1 | Cutscene Exit |


Can be used to force a particular movement pose and behaviour, for example when trying to seamlessly end a canned animation, such as a cutscene or synchronized scene.
```

## Parameters
* **ped**: 
* **state**: The defined motion state to force. See the PED_MOTION_STATE enum for the list of states available.
* **exitstate**: 
* **ForceAIPreCameraUpdate**: 
