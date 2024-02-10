---
ns: ENTITY
aliases: ["0x060d6e96f8b8e48d"]
---
## DOES_ENTITY_HAVE_DRAWABLE

```c
// 0x060D6E96F8B8E48D
bool DOES_ENTITY_HAVE_DRAWABLE(Entity entity);
```

PLAY_ENTITY_ANIM and PLAY_SYNCHRONIZED_ENTITY_ANIM require the entity to have a drawable. You can use this command to check that the entity has a drawable before attempting to play the anim.

