---
ns: STREAMING
aliases: ["0x923cb32a3b874fcb"]
---
## REQUEST_COLLISION_FOR_MODEL

```c
// 0x923CB32A3B874FCB
void REQUEST_COLLISION_FOR_MODEL(Hash modelHash);
```

Tell streaming to request collision for a specific model.

If you need the collision for that object immediately you will need to call [LOAD_ALL_OBJECTS_NOW](#_0xBD6E84632DD4CB3F) and create the object in the same frame, otherwise the collision management code will delete the collision you requested

