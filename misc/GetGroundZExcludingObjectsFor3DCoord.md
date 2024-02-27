---
ns: MISC
aliases: ["0x9e82f0f362881b29"]
---
## GET_GROUND_Z_EXCLUDING_OBJECTS_FOR_3D_COORD

```c
// 0x9E82F0F362881B29
bool GET_GROUND_Z_EXCLUDING_OBJECTS_FOR_3D_COORD(Vector3 Position, float ReturnZ, bool waterAsGround, bool ignoreDistToWaterLevelCheck);
```

Trys to store the Z coordinate the highest ground below the given point. This test excludes any objects that are on the ground. if waterAsGround is set to TRUE water will be included in the check and the height of that will be returned if it is greater than the ground

The command will return TRUE if it finds collision, FALSE if not.


## Parameters
* **Position**: 
* **ReturnZ**: 
* **waterAsGround**: (Default value: `False`)
* **ignoreDistToWaterLevelCheck**: (Default value: `False`)
