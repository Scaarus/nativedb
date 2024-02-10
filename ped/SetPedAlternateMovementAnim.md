---
ns: PED
aliases: ["0x90a43cc281ffab46"]
---
## SET_PED_ALTERNATE_MOVEMENT_ANIM

```c
// 0x90A43CC281FFAB46
void SET_PED_ALTERNATE_MOVEMENT_ANIM(Ped ped, int type, string animDictionary, string anim, float blendDelta, bool looped);
```

```
Swaps the peds straight forward walking anim with the specified anim a new one.

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
* **animDictionary**: the name of the dictionary the anim is in
* **anim**: the name of the anim to use
* **blendDelta**: a float value specifying how fast the anim should blend in if the ped is already moving around defaults to NORMAL_BLEND_IN (see commands_task.sch)
* **looped**: Whether or not the movement anim should play once and then end, or loop until CLEAR_PED_ALTERNATE_MOVEMENT_ANIM is called
