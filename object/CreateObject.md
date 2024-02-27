---
ns: OBJECT
aliases: ["0x509d5878eb39e842"]
---
## CREATE_OBJECT

```c
// 0x509D5878EB39E842
Object CREATE_OBJECT(Hash modelHash, Vector3 NewPosition, bool RegisterAsNetworkObject, bool ScriptHostObject, bool ForceToBeObject);
```

Create an object with an offset (from the root the base) at the given coord.


## Parameters
* **modelHash**: 
* **NewPosition**: 
* **RegisterAsNetworkObject**: The new object will be created and synced on other machines if a network game is running (Default value: `True`)
* **ScriptHostObject**: If true, this object has been created by the host portion of a network script and is vital to that (Default value: `True`)
* **ForceToBeObject**: If true, the object will always be forced to be an object type. This applies when creating an object that uses a door model. If this is false the object will be created as a door door type. (Default value: `False`)
