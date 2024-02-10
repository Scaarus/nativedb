---
ns: ENTITY
aliases: ["0xad738c3085fe7e11"]
---
## SET_ENTITY_AS_MISSION_ENTITY

```c
// 0xAD738C3085FE7E11
void SET_ENTITY_AS_MISSION_ENTITY(bool ScriptHostObject, bool GrabFromOtherScript);
```

Sets a random entity as a mission entity.


## Parameters
* **ScriptHostObject**: If true, this entity has been created by the host portion of a network script and is vital to that
* **GrabFromOtherScript**: If true, this entity will be grabbed off any script that currently owns it
