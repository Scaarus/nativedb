---
ns: CAMERA
aliases: ["0x8bbacbf51da047a8"]
---
## SET_GAMEPLAY_CAM_FOLLOW_PED_THIS_UPDATE

```c
// 0x8BBACBF51DA047A8
void SET_GAMEPLAY_CAM_FOLLOW_PED_THIS_UPDATE(Ped ped);
```

Sets a custom ped to be followed/attached-to by the active gameplay camera this update (only.) Note that this command must be called every update that a custom follow ped is required, as this parameter automatically resets for safety.

