---
ns: PED
aliases: ["0x2b694afcf64e6994"]
---
## MARK_PED_DECORATIONS_AS_CLONED_FROM_LOCAL_PLAYER

```c
// 0x2B694AFCF64E6994
void MARK_PED_DECORATIONS_AS_CLONED_FROM_LOCAL_PLAYER(Ped ped, bool WasClonedFromLocalPlayer);
```

```
Allows the decoration set of a ped cloned from the local player to be marked as such so that tattoosdecals show up in mirrors When cloning from the player ped, this flag is automatically set up by code, but whenever decorations are cleared from the clone, the flag is lost (i.e.: in those cases this commands needs to be called)
```
