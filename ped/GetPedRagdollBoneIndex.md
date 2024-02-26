---
ns: PED
aliases: ["0x2057ef813397a772"]
---
## GET_PED_RAGDOLL_BONE_INDEX

```c
// 0x2057EF813397A772
int GET_PED_RAGDOLL_BONE_INDEX(Ped ped, int ragdollComponent);
```

Returns the bone index of the given ragdoll component. Only used for APPLY_FORCE_TO_ENTITY at the moment.

## ragdollComponent Values:
| Value | Name |
| --- | --- |
| 0 | Pelvis |
| 1 | Thigh L |
| 2 | Calf L |
| 3 | Foot L |
| 4 | Thigh R |
| 5 | Calf R |
| 6 | Foot R |
| 7 | Spine |
| 8 | Spine1 |
| 9 | Spine2 |
| 10 | Spine3 |
| 11 | Clavicle L |
| 12 | Upperarm L |
| 13 | Lowerarm L |
| 14 | Hand L |
| 15 | Clavicle R |
| 16 | Upperarm R |
| 17 | Lowerarm R |
| 18 | Hand R |
| 19 | Neck |
| 20 | Head |
| 21 | Num Components |

