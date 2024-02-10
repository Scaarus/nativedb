---
ns: ENTITY
aliases: ["0xfb71170b7e76acba"]
---
## GET_ENTITY_BONE_INDEX_BY_NAME

```c
// 0xFB71170B7E76ACBA
int GET_ENTITY_BONE_INDEX_BY_NAME(Entity entity, string BoneName);
```

Use when you know the name of a bone and want the bone index for passing to one of the many attach commands.

Returns the bone index if found, -1 otherwise. Therefore you should always check that the bone index is NOT equal to -1 before using it.

