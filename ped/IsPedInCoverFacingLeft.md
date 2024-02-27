---
ns: PED
aliases: ["0x845333b3150583ab"]
---
## IS_PED_IN_COVER_FACING_LEFT

```c
// 0x845333B3150583AB
bool IS_PED_IN_COVER_FACING_LEFT(Ped ped);
```

Checks if the ped is currently facing left in cover. Note you should call [`IS_PED_IN_COVER`](#_0x60DFD0691A170B88) first to ensure the ped is in cover, this will return false if the ped is not in cover.

