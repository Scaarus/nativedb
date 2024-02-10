---
ns: OBJECT
aliases: ["0x9a294b2138abb884"]
---
## CREATE_OBJECT_NO_OFFSET

```c
// 0x9A294B2138ABB884
Object CREATE_OBJECT_NO_OFFSET(Hash modelHash, Vector3 NewPosition, bool RegisterAsNetworkObject, bool ScriptHostObject, bool ForceToBeObject);
```

Create an object with no offset at the given coord.


## Parameters
* **modelHash**: 
* **NewPosition**: 
* **RegisterAsNetworkObject**: The new object will be created and synced on other machines if a network game is running
* **ScriptHostObject**: If true, this object has been created by the host portion of a network script and is vital to that
* **ForceToBeObject**: If true, the object will always be forced to be an object type. This applies when creating an object that uses a door model. If this is false the object will be created as a door door type.
