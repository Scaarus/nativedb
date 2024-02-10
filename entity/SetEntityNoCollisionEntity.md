---
ns: ENTITY
aliases: ["0xa53ed5520c07654a"]
---
## SET_ENTITY_NO_COLLISION_ENTITY

```c
// 0xA53ED5520C07654A
void SET_ENTITY_NO_COLLISION_ENTITY(Entity entity, Entity entity, bool ReactivateWhenNoCollision);
```

```
the bReactivateWhenNoCollision param defines whether collision will reactivate automatically or stay off permanently IF TRUE when there are no possible collisions between the objects it will reactivate so it can collide when no longer penetrating IF FALSE the entities will never collide again

Prevents the first entity from colliding with the second entity
```
