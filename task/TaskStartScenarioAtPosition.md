---
ns: TASK
aliases: ["0xfa4efc79f69d4f07"]
---
## TASK_START_SCENARIO_AT_POSITION

```c
// 0xFA4EFC79F69D4F07
void TASK_START_SCENARIO_AT_POSITION(string ScenarioName, Vector3 vPosition, float fHeading, int iTimeToLeave, bool PlayIntroClip, bool Warp);
```

The ped will move or warp to the position and heading given, then start the scenario passed.

scenario is chosen fromhttp://10.11.23.14/wiki/index.php?title=SCENARIO_STRINGS The z coord of vPosition should be the ground position plus the ped's ground to root offset.


## Parameters
* **ScenarioName**: 
* **vPosition**: 
* **fHeading**: 
* **iTimeToLeave**: (Default value: `0`)
* **PlayIntroClip**: (Default value: `False`)
* **Warp**: (Default value: `True`)
