---
ns: WATER
aliases: ["0x2b3451fa1e3142e2"]
---
## TEST_VERTICAL_PROBE_AGAINST_ALL_WATER

```c
// 0x2B3451FA1E3142E2
script_water_test_result TEST_VERTICAL_PROBE_AGAINST_ALL_WATER(Vector3 StartPos, int BlockingFlags, float Height);
```

Find the height of land/water at a given xy coordinate.

## Return Type Values:
| Value | Name |
| --- | --- |
| 0 | None |
| 1 | Water |
| 2 | Blocked |


## Parameters
* **StartPos**: the start of the probe (intersections above this Z-coordinate will not be counted)
* **BlockingFlags**: things that can block the probe from hitting water (see SCRIPT_INCLUDE flags in commands_shapetest.sch)
* **Height**: out parameter filled with the height of the probe intersection (as long as the result isn't SCRIPT_WATER_TEST_RESULT_NONE)
