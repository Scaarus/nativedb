---
ns: ENTITY
aliases: ["0x8524a8b0171d5e07"]
---
## SET_ENTITY_ROTATION

```c
// 0x8524A8B0171D5E07
void SET_ENTITY_ROTATION(Entity entity, Vector3 NewRotation, int RotOrder, bool DoDeadCheck);
```

Sets the entity's rotation.

## RotOrder Values:
| Value | Name |
| --- | --- |
| 0 | Xyz |
| 1 | Xzy |
| 2 | Yxz |
| 3 | Yzx |
| 4 | Zxy |
| 5 | Zyx |
| 6 | Max |

