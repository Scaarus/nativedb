---
ns: WATER
aliases: ["0xffa5d878809819db"]
---
## TEST_PROBE_AGAINST_WATER

```c
// 0xFFA5D878809819DB
bool TEST_PROBE_AGAINST_WATER(Vector3 StartPos, Vector3 EndPos, Vector3 IntersectionPos);
```

Test a directed probe against the water


## Parameters
* **StartPos**: the start of the probe
* **EndPos**: the end of the probe
* **IntersectionPos**: out paramter filled with the intersection position on the water. It will only be valid if the function returns truex
