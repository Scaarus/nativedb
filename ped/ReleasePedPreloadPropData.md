---
ns: PED
aliases: ["0xf79f9def0aade61a"]
---
## RELEASE_PED_PRELOAD_PROP_DATA

```c
// 0xF79F9DEF0AADE61A
void RELEASE_PED_PRELOAD_PROP_DATA(Ped ped);
```

Releases the assets set with [SET_PED_PRELOAD_PROP_DATA](#_0x2B16A3BFF1FBCE49). More...

Note that prop data set with SET_PED_PRELOAD_PROP_DATA counts towards the script memory budget. For this reason it is important to use this command to release these assets as soon as you don't need them anymore. In fact, you can call this command as soon as you have set the same prop with [SET_PED_PROP_INDEX](#_0x93376B65A266EB5F) since at that point the assets will be rendered on the ped and have references to keep them in memory.

