---
ns: PED
aliases: ["0xd76632d99e4966c8"]
---
## SET_PED_TO_RAGDOLL_WITH_FALL

```c
// 0xD76632D99E4966C8
bool SET_PED_TO_RAGDOLL_WITH_FALL(int MinTime, int MaxTime, int nFallType, Vector3 vecDirection, float fGroundHeight, Vector3 vecGrab1, Vector3 vecGrab2);
```

this performs the same function as std SET_PED_TO_RAGDOLL, but gives them a specific task, which controls them to fall off a high place, fall down stairs etc,

## nFallType Values:
| Value | Name |
| --- | --- |
| 0 | From High |
| 1328 | Over Wall Fall Over Wall |
| 1329 | Down Stairs Fall Down Stairs |
| 1330 | Die Types Not To Be Used, Marker For Start Of Die Types |
| 1331 | Die From High As Above But Die When Done |
| 1332 | Die Over Wall "	" |
| 1333 | Die Down Stairs "	" |


vecDirection specifies the direction the ped should stagger and fall ground height specifies the height they're expected to fall down to grab points are optional, pass in zero to ignore grab

