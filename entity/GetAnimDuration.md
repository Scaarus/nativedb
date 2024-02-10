---
ns: ENTITY
aliases: ["0xfeddf04d62b8d790"]
---
## GET_ANIM_DURATION

```c
// 0xFEDDF04D62B8D790
float GET_ANIM_DURATION(string pAnimDictName, string pAnimName);
```

Gets the total length of the anim in seconds.

Unlike GET_ENTITY_ANIM_TOTAL_TIME above, the anim does not need to be playing on an entity. However, you must load the anim dictionary prior to calling this, or the command will assert.

