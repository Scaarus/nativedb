---
ns: PED
aliases: ["0x8844bbfce30aa9e9"]
---
## CLEAR_PED_ALTERNATE_WALK_ANIM

```c
// 0x8844BBFCE30AA9E9
void CLEAR_PED_ALTERNATE_WALK_ANIM(Ped ped, float blendDelta);
```

```
MAkes the ped go back to using its original walk anim.

Specifies a new walking animation to use when the ped is walking around
```

## Parameters
* **ped**: 
* **blendDelta**: a float value specifying how fast the anim should blend back to the normal walk defaults to NORMAL_BLEND_OUT (see commands_task.sch)
