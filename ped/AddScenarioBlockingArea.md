---
ns: PED
aliases: ["0x1b5c85c612e5256e"]
---
## ADD_SCENARIO_BLOCKING_AREA

```c
// 0x1B5C85C612E5256E
Scenario_Blocking ADD_SCENARIO_BLOCKING_AREA(Vector3 vMax, bool Network, bool CancelActive, bool BlockPeds, bool BlockVehicles);
```

```
Sets an area where scenarios are blocked (This can be optionally networked to other players, for use in scripts that aren't run on all machines)

bCancelActive = should this call cause peds already using points in the specified area to leave their points bBlockPeds = does this area affect ped scenarios (either this or bBlockPeds must be TRUE) bBlockVehicles = does this area affect vehicle scenarios
```
