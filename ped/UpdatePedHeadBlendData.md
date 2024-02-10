---
ns: PED
aliases: ["0x723538f61c647c5a"]
---
## UPDATE_PED_HEAD_BLEND_DATA

```c
// 0x723538F61C647C5A
void UPDATE_PED_HEAD_BLEND_DATA(Ped ped, float headBlend, float texBlend, float varBlend);
```

```
Updates the blend values on a previously set ped head blend. This is much cheaper and faster than using SET_PED_HEAD_BLEND_DATA, which should only be used once
```
