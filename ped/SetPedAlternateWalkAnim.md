---
ns: PED
aliases: ["0x6c60394cb4f75e9a"]
---
## SET_PED_ALTERNATE_WALK_ANIM

```c
// 0x6C60394CB4F75E9A
void SET_PED_ALTERNATE_WALK_ANIM(Ped ped, string animDictionary, string anim, float blendDelta, bool looped);
```

Swaps the peds straight forward walking anim with the specified anim a new one.

Specifies a new walking animation to use when the ped is walking around


## Parameters
* **ped**: 
* **animDictionary**: the name of the dictionary the anim is in
* **anim**: the name of the anim to use
* **blendDelta**: a float value specifying how fast the anim should blend in if the ped is already walking around defaults to NORMAL_BLEND_IN (see commands_task.sch) (Default value: `8`)
* **looped**: Whether or not the walk anim should play once and then end, or loop until CLEAR_PED_ALTERNATE_WALK_ANIM is called (Default value: `True`)
