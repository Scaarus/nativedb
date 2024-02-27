---
ns: VEHICLE
aliases: ["0xaf35d0d2583051b0"]
---
## CREATE_VEHICLE

```c
// 0xAF35D0D2583051B0
Vehicle CREATE_VEHICLE(Hash modelHash, Vector3 Position, float fVehicleHeading, bool RegisterAsNetworkObject, bool ScriptHostObject, bool IgnoreGroundCheck);
```

Ceates a vehicle at a coord with a heading

Model_names is taken from Model_enums.sch,


## Parameters
* **modelHash**: 
* **Position**: 
* **fVehicleHeading**: (Default value: `0`)
* **RegisterAsNetworkObject**: The new object will be created and synced on other machines if a network game is running (Default value: `True`)
* **ScriptHostObject**: If true, this object has been created by the host portion of a network script and is vital to that (Default value: `True`)
* **IgnoreGroundCheck**: (Default value: `False`)
