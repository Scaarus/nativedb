---
ns: NETWORK
aliases: ["0x7cd6bc4c2bbdd526"]
---
## NETWORK_CREATE_SYNCHRONISED_SCENE

```c
// 0x7CD6BC4C2BBDD526
int NETWORK_CREATE_SYNCHRONISED_SCENE(Vector3 sceneOrientation, int RotOrder, bool HoldLastFrame, bool Looped, float PhaseToStopScene, float PhaseToStartScene, float StartRate);
```

Creates a new networked synchronised scene - this is similar to normal synchronised scenes but a lot more network friendly. Call this on a one machine only, add any peds (regardless of whether they are locally controlled or not) via the NETWORK_ADD_PED_TO_SYNCHRONISED_SCENE, and then start it running with the NETWORK_START_SYNCHRONISED_SCENE command. The scene will automatically be synced to all machines.

## RotOrder Values:
| Value | Name |
| --- | --- |
| 0 | Xyz |
| 1 | Xzy |
| 2 | Yxz |
| 3 | Yzx |
| 4 | Zxy |
| 5 | Zyx |
| 6 | Max |

