---
ns: TASK
aliases: ["0xae032f8bba959e90"]
---
## TASK_STAND_GUARD

```c
// 0xAE032F8BBA959E90
void TASK_STAND_GUARD(Vector3 vDefendPosition, float fHeading, string context);
```

```
Tells the ped to defend the given position.

Will stay within fPositionProximity metres to the given position, unless attacked; then ped will react according to its set decision makers until combat is ended, then will return to given position. Heading given by fHeading, measured in degrees, and only used when the Ped is at the main vDefendPosition. Context is used to stream in ambient animations or playing specific scenarios whilst the guard is guarding, defaults to a stationary scenario with stand guard ambient anims
```
