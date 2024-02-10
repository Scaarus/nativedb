---
ns: SHAPETEST
aliases: ["0x377906d8a31e5586"]
---
## START_EXPENSIVE_SYNCHRONOUS_SHAPE_TEST_LOS_PROBE

```c
// 0x377906D8A31E5586
Shapetest START_EXPENSIVE_SYNCHRONOUS_SHAPE_TEST_LOS_PROBE(Vector3 StartPos, Vector3 EndPos, int LOSFlags, Entity entity, int Options);
```

NOTES: !!!!! WARNING !!!!! THIS COMMAND IS MUCH MORE EXPENSIVE THAN USING THE ASYNCHRONOUS VERSION (START_SHAPE_TEST_LOS_PROBE). PLEASE TRY THAT FIRST!

Returns SHAPETEST_INDEX of 0 if it fails to create the shapetest request (there is a limit to the number that can be in the system)

