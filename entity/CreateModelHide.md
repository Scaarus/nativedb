---
ns: ENTITY
aliases: ["0x8a97bca30a0ce478"]
---
## CREATE_MODEL_HIDE

```c
// 0x8A97BCA30A0CE478
void CREATE_MODEL_HIDE(Vector3 pos, float radius, Hash modelHash, bool SurviveMapReload);
```

```
This is intended as a replacement for the old commands for disabling visibility and collisions for an entity. Improvements include support for objects, and support for automatic persistence across dummy conversion, map data streaming etc.

any building or object with the corresponding model name, which intersects with the specified sphere, will have its model hidden and physics disabled. Optionally this swap can automatically be applied as map data streams in and out, ensuring a persistent model hide at the position specified.

Creates an active model hide for a building or object
```
