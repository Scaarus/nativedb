---
ns: ENTITY
aliases: ["0xda95ea3317cc5064"]
---
## DOES_ENTITY_HAVE_PHYSICS

```c
// 0xDA95EA3317CC5064
bool DOES_ENTITY_HAVE_PHYSICS(Entity entity);
```

CHecks that an object has physics.

Before calling physics commands e.g SET_ENTITY_VELOCITY you have to check that the entity has physics. Physics are streamed in sperateley from the drawable object, though entity physics near the player are streamed in automatically.

