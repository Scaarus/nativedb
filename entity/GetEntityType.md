---
ns: ENTITY
aliases: ["0x8acd366038d14505"]
---
## GET_ENTITY_TYPE

```c
// 0x8ACD366038D14505
entity_type GET_ENTITY_TYPE(Entity entity);
```

```
Returns the type of the entity (ped, vehicle, or object) or ET_NONE if none of the above.

Possible return values:
| Index | Name |
| --- | --- |
| 0 | None |
| 1 | Ped |
| 2 | Vehicle |
| 3 | Object |
```
