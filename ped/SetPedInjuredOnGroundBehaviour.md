---
ns: PED
aliases: ["0xec4b4b3b9908052a"]
---
## SET_PED_INJURED_ON_GROUND_BEHAVIOUR

```c
// 0xEC4B4B3B9908052A
void SET_PED_INJURED_ON_GROUND_BEHAVIOUR(Ped ped, float duration);
```

```
This command overrides the random injured on ground behavior on the provided ped.

duration : the amount of time the ped will lie injured on the ground before dying

Use this to force the ped to use the injured on ground nm behaviour when he dies (note, a headshot will still override this currently).
```
