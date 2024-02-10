---
ns: PED
aliases: ["0x79cfd9827cc979b6"]
---
## GET_PED_PARACHUTE_STATE

```c
// 0x79CFD9827CC979B6
ped_parachute_state GET_PED_PARACHUTE_STATE(Ped ped);
```

```
Gets the current state of the Parachuting Ped (returns PPS_INVALID if the Ped isn't Parachuting).

Possible return values:
| Index | Name |
| --- | --- |
| -1 | Invalid |
| 0 | Skydiving |
| 1 | Deploying |
| 2 | Parachuting |
| 3 | Landing |
```
