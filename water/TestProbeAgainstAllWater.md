---
ns: WATER
aliases: ["0x8974647ed222ea5f"]
---
## TEST_PROBE_AGAINST_ALL_WATER

```c
// 0x8974647ED222EA5F
script_water_test_result TEST_PROBE_AGAINST_ALL_WATER(Vector3 StartPos, Vector3 EndPos, int BlockingFlags);
```

Test a directed probe against all water, including rivers

## Return Type Values:
| Value | Name |
| --- | --- |
| 0 | None |
| 1 | Water |
| 2 | Blocked |


## Parameters
* **StartPos**: the start of the probe
* **EndPos**: the end of the probe
* **BlockingFlags**: things that can block the probe from hitting water (see SCRIPT_INCLUDE flags in commands_shapetest.sch)
