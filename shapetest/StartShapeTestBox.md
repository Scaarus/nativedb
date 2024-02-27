---
ns: SHAPETEST
aliases: ["0xfe466162c4401d18"]
---
## START_SHAPE_TEST_BOX

```c
// 0xFE466162C4401D18
Shapetest START_SHAPE_TEST_BOX(Vector3 scrVecPos, Vector3 scrVecDims, Vector3 eulerAngles, int RotOrder, int LOSFlags, Entity entity, int Options);
```

## Values for `RotOrder`:
| Value | Name |
| --- | --- |
| 0 | Xyz |
| 1 | Xzy |
| 2 | Yxz |
| 3 | Yzx |
| 4 | Zxy |
| 5 | Zyx |


Returns SHAPETEST_INDEX of 0 if it fails to create the shapetest request (there is a limit to the number that can be in the system)


## Parameters
* **scrVecPos**: 
* **scrVecDims**: 
* **eulerAngles**: 
* **RotOrder**: (Default value: `Yxz`)
* **LOSFlags**: (Default value: `Script_Include_Mover`)
* **entity**: (Default value: `Null`)
* **Options**: (Default value: `Script_Shapetest_Option_Ignore_No_Collision`)
