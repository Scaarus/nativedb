---
ns: TASK
aliases: ["0x788756d73ac2e07c"]
---
## IS_SCENARIO_OCCUPIED

```c
// 0x788756D73AC2E07C
bool IS_SCENARIO_OCCUPIED(float fRange, bool OnlyUsersActuallyAtScenario);
```

Check if the closest scenario to a given point is occupied by some user.

Returns FALSE if no scenario was even found in this location (use DOES_SCENARIO_EXIST_IN_AREA to check, if needed)


## Parameters
* **fRange**: max distance from position to look for scenario
* **OnlyUsersActuallyAtScenario**: If true, only consider users that have actually arrived, not users that are on their way to the scenario
