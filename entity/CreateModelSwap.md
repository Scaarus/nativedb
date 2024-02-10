---
ns: ENTITY
aliases: ["0x92c47782fda8b2a3"]
---
## CREATE_MODEL_SWAP

```c
// 0x92C47782FDA8B2A3
void CREATE_MODEL_SWAP(Vector3 pos, float radius, Hash modelHash, Hash modelHash, bool SurviveMapReload);
```

This is intended as a replacement for the old building swap system. Improvements include support for objects, and support for automatic persistence across dummy conversion, map data streaming etc.

any building or object with the corresponding model name, which intersects with the specified sphere, will have its model swapped to the new model. Optionally this swap can automatically be applied as map data streams in and out, ensuring a persistent model swap at the position specified.

Creates an active model swap for a building or object

