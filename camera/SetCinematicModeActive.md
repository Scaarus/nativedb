---
ns: CAMERA
aliases: ["0xdcf0754ac3d6fd4e"]
---
## SET_CINEMATIC_MODE_ACTIVE

```c
// 0xDCF0754AC3D6FD4E
void SET_CINEMATIC_MODE_ACTIVE(bool Active);
```

```
Sets the cinematic mode to active. Will only render if there is a valid cinematic context else will be reset.

If there is a cinematic camera rendering, this can be overriden by the player using quick toggle or pressing select
```
