---
ns: TASK
aliases: ["0x0ae4086104e067b1"]
---
## TASK_JUMP

```c
// 0x0AE4086104E067B1
void TASK_JUMP(Ped ped, bool UsePlayerLaunch, bool DoSuperJump, bool UseFullSuperJumpForce);
```

```
Force a char to jump.

If UsePlayerLaunchForce is TRUE then the ped will use the same launch force as the player. If UsePlayerLaunchForce is FALSE and the ped isn’t the player then the ped will jump using a smaller launch force.
```
