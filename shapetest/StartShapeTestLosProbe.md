---
ns: SHAPETEST
aliases: ["0x7ee9f5d83dd4f90e"]
---
## START_SHAPE_TEST_LOS_PROBE

```c
// 0x7EE9F5D83DD4F90E
Shapetest START_SHAPE_TEST_LOS_PROBE(Vector3 StartPos, Vector3 EndPos, int LOSFlags, Entity entity, int Options);
```

NOTES:

Returns SHAPETEST_INDEX of 0 if it fails to create the shapetest request (there is a limit to the number that can be in the system)

