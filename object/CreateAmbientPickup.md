---
ns: OBJECT
aliases: ["0x673966a0c0fd7171"]
---
## CREATE_AMBIENT_PICKUP

```c
// 0x673966A0C0FD7171
Object CREATE_AMBIENT_PICKUP(Vector3 NewPosition, int PlacementFlags, int Amount, Hash modelHash, bool CreateAsScriptObject, bool ScriptHostObject);
```

Creates a pickup similar to those dropped by dead peds. These types of pickups are part of the ambient population and will get removed if the player moves too far away from them. They cannot be referenced by the script and will remain if the script terminates. *** UNLESS bCreateAsScriptObject is set! ***


## Parameters
* **NewPosition**: World Coordinates of the pickup
* **PlacementFlags**: (Default value: `0`)
* **Amount**: 
* **modelHash**: (Default value: `0`)
* **CreateAsScriptObject**: (Default value: `False`)
* **ScriptHostObject**: Only used if bCreateAsScriptObject is set to true. If true, this object has been created by the host portion of a network script and is vital to that (Default value: `True`)
