---
ns: SHAPETEST
aliases: ["0xe6ac6c45fbe83004"]
---
## START_SHAPE_TEST_SWEPT_SPHERE

```c
// 0xE6AC6C45FBE83004
Shapetest START_SHAPE_TEST_SWEPT_SPHERE(Vector3 scrVecPos, Vector3 scrVecEndPos, float fRadius, int LOSFlags, Entity entity, int Options);
```

Returns SHAPETEST_INDEX of 0 if it fails to create the shapetest request (there is a limit to the number that can be in the system)


## Parameters
* **scrVecPos**: 
* **scrVecEndPos**: 
* **fRadius**: 
* **LOSFlags**: (Default value: `Script_Include_Mover`)
* **entity**: (Default value: `Null`)
* **Options**: (Default value: `Script_Shapetest_Option_Ignore_No_Collision`)
