---
ns: PED
aliases: ["0xd8d19675ed5fbdce"]
---
## CLEAR_PED_ALTERNATE_MOVEMENT_ANIM

```c
// 0xD8D19675ED5FBDCE
void CLEAR_PED_ALTERNATE_MOVEMENT_ANIM(Ped ped, int type, float blendDelta);
```

```
MAkes the ped go back to using its original walk anim.

Possible values for type:
| Index | Name |
| --- | --- |
| 254 | Idle |
| 255 | Walk |
| 256 | Run |
| 257 | Sprint |


Specifies a new movement animation to use when the ped is moving around
```

## Parameters
* **ped**: 
* **type**: 
* **blendDelta**: a float value specifying how fast the anim should blend back to the normal walk defaults to NORMAL_BLEND_OUT (see commands_task.sch)
