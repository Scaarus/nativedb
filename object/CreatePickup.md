---
ns: OBJECT
aliases: ["0xfba08c503dd5fa58"]
---
## CREATE_PICKUP

```c
// 0xFBA08C503DD5FA58
Pickup CREATE_PICKUP(Vector3 NewPosition, int PlacementFlags, int Amount, bool ScriptHostObject, Hash modelHash);
```

Creates a pickup spawner which can be referenced by the script and will spawn a pickup whenever the player gets near. This spawner can also regenerate the pickup after it is collected. The spawner is removed when the script terminates.


## Parameters
* **NewPosition**: World Coordinates of the pickup
* **PlacementFlags**: (Default value: `0`)
* **Amount**: 
* **ScriptHostObject**: If true, this object has been created by the host portion of a network script and is vital to that (Default value: `True`)
* **modelHash**: (Default value: `0`)
