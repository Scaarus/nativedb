---
ns: ENTITY
aliases: ["0x8acd366038d14505"]
---
## GET_ENTITY_TYPE

```c
// 0x8ACD366038D14505
int GET_ENTITY_TYPE(Entity entity);
```

Returns the type of the entity (ped, vehicle, or object) or ET_NONE if none of the above.

## Return Type Values:
| Value | Name |
| --- | --- |
| 0 | None |
| 1 | Ped |
| 2 | Vehicle |
| 3 | Object |

