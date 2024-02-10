---
ns: PED
aliases: ["0xceda60a74219d064"]
---
## SET_PED_SHOULD_PROBE_FOR_SCENARIO_EXITS_IN_ONE_FRAME

```c
// 0xCEDA60A74219D064
void SET_PED_SHOULD_PROBE_FOR_SCENARIO_EXITS_IN_ONE_FRAME(Ped ped, bool InOneFrame);
```

```
Control how the ped probes to find a valid exit point.

When this ped is performing their scenario exit probes, all of the probes will be checked in one frame. Use with caution! This can cause performance issues if overused.
```
