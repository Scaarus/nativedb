---
ns: SHAPETEST
aliases: ["0x052837721a854ec7"]
---
## START_SHAPE_TEST_BOUNDING_BOX

```c
// 0x052837721A854EC7
Shapetest START_SHAPE_TEST_BOUNDING_BOX(Entity entity, int LOSFlags, int Options);
```

Returns SHAPETEST_INDEX of 0 if it fails to create the shapetest request (there is a limit to the number that can be in the system)


## Parameters
* **entity**: 
* **LOSFlags**: (Default value: `Los_Flags_Bounding_Box`)
* **Options**: (Default value: `Script_Shapetest_Option_Ignore_No_Collision`)
