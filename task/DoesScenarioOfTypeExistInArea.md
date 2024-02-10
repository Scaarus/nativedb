---
ns: TASK
aliases: ["0x0a9d0c2a3bbc86c1"]
---
## DOES_SCENARIO_OF_TYPE_EXIST_IN_AREA

```c
// 0x0A9D0C2A3BBC86C1
bool DOES_SCENARIO_OF_TYPE_EXIST_IN_AREA(string scenarioType, float fRange, bool MustBeFree);
```

Returns true if there is a scenario of the specific type in the area given

bMustBeFree is true it will only return true if the point is not in use.

