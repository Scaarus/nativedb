---
ns: PED
aliases: ["0x26d83693ed99291c"]
---
## SET_PED_HELMET_PROP_INDEX

```c
// 0x26D83693ED99291C
void SET_PED_HELMET_PROP_INDEX(Ped ped, int OverwriteHelmetPropIndex, bool IncludeBicycles);
```

Sets the helmet prop index to be used instead of default, -1 uses default. This can't be set if the ped has a helmet on already.

In MP this is can only be used for the bikequad helmets bought in a shop.

