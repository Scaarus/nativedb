---
ns: PED
aliases: ["0xffc24b988b938b38"]
---
## SET_FACIAL_IDLE_ANIM_OVERRIDE

```c
// 0xFFC24B988B938B38
void SET_FACIAL_IDLE_ANIM_OVERRIDE(Ped ped, string pOverrideIdleClipName, string pOverrideIdleClipDictName);
```

```
Overrides any playing facial idle, to play this until cleared with . If dictionary name is not specified then it will look in the ped's current facial clipset for it.
```
