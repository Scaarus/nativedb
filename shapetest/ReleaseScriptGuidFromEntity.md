---
ns: SHAPETEST
aliases: ["0x2b3334bca57cd799"]
---
## RELEASE_SCRIPT_GUID_FROM_ENTITY

```c
// 0x2B3334BCA57CD799
void RELEASE_SCRIPT_GUID_FROM_ENTITY(Entity entity);
```

GET_SHAPE_TEST_RESULT and GET_SHAPE_TEST_RESULT_INCLUDING_MATERIAL create a temporary script GUID for the EntityIndex that they return. Call this to free that script GUID. This command won't do anything if it's called on a script-created entity so you shouldn't need to check that yourself before calling this command.

