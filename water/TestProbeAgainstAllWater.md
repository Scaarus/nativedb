---
ns: WATER
aliases: ["0x8974647ed222ea5f"]
---
## TEST_PROBE_AGAINST_ALL_WATER

```c
// 0x8974647ED222EA5F
int TEST_PROBE_AGAINST_ALL_WATER(Vector3 StartPos, Vector3 EndPos, int BlockingFlags, Vector3 IntersectionPos);
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
* **IntersectionPos**: out paramter filled with the intersection position (as long as the result isn't SCRIPT_WATER_TEST_RESULT_NONE)
