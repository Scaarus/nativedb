---
ns: ENTITY
aliases: ["0x1f0b79228e461ec9"]
---
## IS_ENTITY_PLAYING_ANIM

```c
// 0x1F0B79228E461EC9
bool IS_ENTITY_PLAYING_ANIM(string AnimDictName, string AnimName, int type);
```

Checks if the entity is currently playing the animation.

## type Values:
| Value | Name |
| --- | --- |
| 1 | Script |
| 2 | Synced Scene |
| 3 | Default |
| 4 | Code |


## Parameters
* **AnimDictName**: 
* **AnimName**: 
* **type**: (Default value: `Default`)
