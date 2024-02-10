---
ns: OBJECT
aliases: ["0xe143fa2249364369"]
---
## GET_CLOSEST_OBJECT_OF_TYPE

```c
// 0xE143FA2249364369
Object GET_CLOSEST_OBJECT_OF_TYPE(Vector3 scrVecCentrePosition, float Radius, Hash modelHash, bool RegisterAsScriptObject, bool ScriptHostObject, bool RegisterAsNetworkObject);
```

```
Grabs the closest object (or dummy object) with the specified model. The object is set as a mission object. You can't delete this object. You can set it as no longer needed. If no object is found in the range then NULL is returned. A dummy object will first be converted to a real object.
```

## Parameters
* **scrVecCentrePosition**: 
* **Radius**: 
* **modelHash**: 
* **RegisterAsScriptObject**: The new object will be registered with the script
* **ScriptHostObject**: If true, this object has been created by the host portion of a network script and is vital to that
* **RegisterAsNetworkObject**: The new object will be created and synced on other machines if a network game is running
