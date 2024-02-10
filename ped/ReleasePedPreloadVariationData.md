---
ns: PED
aliases: ["0x5aab586ffec0fd96"]
---
## RELEASE_PED_PRELOAD_VARIATION_DATA

```c
// 0x5AAB586FFEC0FD96
void RELEASE_PED_PRELOAD_VARIATION_DATA(Ped ped);
```

Releases the assets set with SET_PED_PRELOAD_VARIATION_DATA. More...

Note that variation data set with SET_PED_PRELOAD_VARIATION_DATA counts towards the script memory budget. For this reason it is important to use this command to release these assets as soon as you don't need them anymore. In fact, you can call this command as soon as you have set the same variation with SET_PED_COMPONENT_VARIATION since at that point the assets will be rendered on the ped and have references to keep them in memory.

