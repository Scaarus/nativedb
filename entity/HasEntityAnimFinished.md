---
ns: ENTITY
aliases: ["0x20b711662962b472"]
---
## HAS_ENTITY_ANIM_FINISHED

```c
// 0x20B711662962B472
bool HAS_ENTITY_ANIM_FINISHED(Entity entity, string pAnimDictName, string pAnimName, int animType);
```

Checks if the anim specified is being held on the last frame.

## animType Values:
| Value | Name |
| --- | --- |
| 1 | Script |
| 2 | Synced Scene |
| 3 | Default |
| 4 | Code |


This command will only ever return true for anims that hold at the end (i.e. anims that loop or end automatically will always return false)

