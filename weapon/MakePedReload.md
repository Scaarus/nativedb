---
ns: WEAPON
aliases: ["0x20ae33f3ac9c0033"]
---
## MAKE_PED_RELOAD

```c
// 0x20AE33F3AC9C0033
bool MAKE_PED_RELOAD(Ped ped);
```

```
Make a (player) ped reload at the first opportunity and return true, if holding a reloadable weapon that's not full already, or otherwise, return false.

The initial version of this command only works for the player, can be extended to AI if needed.
```
