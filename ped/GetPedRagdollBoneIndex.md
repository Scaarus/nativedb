---
ns: PED
aliases: ["0x2057ef813397a772"]
---
## GET_PED_RAGDOLL_BONE_INDEX

```c
// 0x2057EF813397A772
int GET_PED_RAGDOLL_BONE_INDEX(Ped ped, int ragdollComponent);
```

```
Returns the bone index of the given ragdoll component. Only used for APPLY_FORCE_TO_ENTITY at the moment.

Possible values for ragdollComponent:
| Index | Name |
| --- | --- |
| 0 | Pelvis |
| 6 | Thigh L |
| 7 | Calf L |
| 8 | Foot L |
| 9 | Thigh R |
| 10 | Calf R |
| 11 | Foot R |
| 12 | Spine |
| 13 | Spine1 |
| 14 | Spine2 |
| 15 | Spine3 |
| 16 | Clavicle L |
| 17 | Upperarm L |
| 18 | Lowerarm L |
| 19 | Hand L |
| 20 | Clavicle R |
| 21 | Upperarm R |
| 22 | Lowerarm R |
| 23 | Hand R |
| 24 | Neck |
| 25 | Head |
| 26 | Num Components |
```
