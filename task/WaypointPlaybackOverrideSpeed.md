---
ns: TASK
aliases: ["0x7d7d2b47fa788e85"]
---
## WAYPOINT_PLAYBACK_OVERRIDE_SPEED

```c
// 0x7D7D2B47FA788E85
void WAYPOINT_PLAYBACK_OVERRIDE_SPEED(Ped ped, float fMoveBlendRatio, bool DontAllowSlowingForCorners);
```

```
Overrides the speed at which the ped moves, ignoring the speeds recorded in the route bDontAllowSlowingForCorners - allows the ped to slow for corners; without this peds may have trouble keeping to their routes.

fMoveBlendRatio (0.0 = still, 1.0 = walk, 2.0 = run, 3.0 = sprint)
```
