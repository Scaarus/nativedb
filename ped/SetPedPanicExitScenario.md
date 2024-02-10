---
ns: PED
aliases: ["0xfe07ff6495d52e2a"]
---
## SET_PED_PANIC_EXIT_SCENARIO

```c
// 0xFE07FF6495D52E2A
bool SET_PED_PANIC_EXIT_SCENARIO(Ped ped, Vector3 vDangerPosition);
```

```
Causes a ped to panic exit a scenario.

The ped will react as if something dangerous happened at the given position.

Causes a ped to exit a scenario (via playing a panic outro if possible, otherwise normal) immediately, if possible. The ped must currently be using a scenario. Returns a boolean indicating whether the exit of the scenario has begun successfully. Does not queue a response task to be used after the exit, that must be done separately. It can be run on peds using CTaskUseScenario or CTaskCowerScenario.
```
