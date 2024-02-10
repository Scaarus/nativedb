---
ns: ENTITY
aliases: ["0x150e808b375a385a"]
---
## CREATE_FORCED_OBJECT

```c
// 0x150E808B375A385A
void CREATE_FORCED_OBJECT(Vector3 pos, float radius, Hash modelHash, bool SurviveMapReload);
```

```
Sometimes (e.g. when following an NPC-driven vehicle ahead of you) it is necessary to force particular barriers to become real objects so the vehicle you are following smashes through them properly rather than passing through without collision.

any dummy object with the corresponding model name, which intersects with the specified sphere, will be forced to become a real dynamic object (rather than a dummy object)

Creates a persistent force-to-object effect on map
```
