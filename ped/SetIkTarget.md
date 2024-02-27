---
ns: PED
aliases: ["0xc32779c16fceecd9"]
---
## SET_IK_TARGET

```c
// 0xC32779C16FCEECD9
void SET_IK_TARGET(Ped ped, int IKPart, Entity entity, int TargetBone, Vector3 TargetOffset, int Flags, int BlendInTimeMS, int BlendOutTimeMS);
```

Sets the IK target for a given IK part belonging to the ped. The IK target will only be valid for one update, so it needs to be set for as long as it is needed (to avoid IK targets not being cleared and getting stuck enabled).

## Values for `IKPart`:
| Value | Name |
| --- | --- |
| 0 | Invalid |
| 1 | Head |
| 2 | Spine |
| 3 | Arm Left |
| 4 | Arm Right |
| 5 | Leg Left |
| 6 | Leg Right |


## Values for `Flags`:
| Value | Name |
| --- | --- |
| 0 | Default |
| 1 | Arm Target Wrt Handbone |
| 2 | Arm Target Wrt Pointhelper |
| 4 | Arm Target Wrt Ikhelper |
| 8 | Ik Tag Mode Normal |
| 16 | Ik Tag Mode Allow |
| 32 | Ik Tag Mode Block |
| 64 | Arm Use Orientation |


## Parameters
* **ped**: 
* **IKPart**: IK part of ped to set IK target for (see IK_PART type).
* **entity**: 
* **TargetBone**: Bone tag representing target entity bone to target. Set to -1 for no target bone. VECTOR
* **TargetOffset**: If target entity is NULL, TargetOffset is assumed to be world coordinates. If target entity is not NULL, TargetOffset is an offset from the target entity. If target entity is not NULL and TargetBone is not -1, TargetOffset is an offset relative to the bone. Set to (0,0,0) for no offset. IK_TARGET_FLAGS
* **Flags**: Optional flags to set (see IK_TARGET_FLAGS type). Otherwise, set to 0. INT
* **BlendInTimeMS**: Blend in time in MS. Set to -1 for default blend in time. Set to 0 for instant blend in time. INT
* **BlendOutTimeMS**: Blend out time in MS. Set to -1 for default blend out time. Set to 0 for instant blend out time.
