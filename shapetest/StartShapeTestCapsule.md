---
ns: SHAPETEST
aliases: ["0x28579d1b8f8aac80"]
---
## START_SHAPE_TEST_CAPSULE

```c
// 0x28579D1B8F8AAC80
Shapetest START_SHAPE_TEST_CAPSULE(Vector3 scrVecPos, Vector3 scrVecEndPos, float fRadius, int LOSFlags, Entity entity, int Options);
```

Returns SHAPETEST_INDEX of 0 if it fails to create the shapetest request (there is a limit to the number that can be in the system)


## Parameters
* **scrVecPos**: 
* **scrVecEndPos**: 
* **fRadius**: 
* **LOSFlags**: (Default value: `Script_Include_Mover`)
* **entity**: (Default value: `Null`)
* **Options**: (Default value: `Script_Shapetest_Option_Ignore_No_Collision`)
