---
ns: PED
aliases: ["0xf1550c4bd22582e2"]
---
## SET_PED_HELMET_TEXTURE_INDEX

```c
// 0xF1550C4BD22582E2
void SET_PED_HELMET_TEXTURE_INDEX(Ped ped, int OverwriteHelmetTexIndex);
```

Sets the helmet texture index to be used instead of default, -1 uses default. This can't be set if the ped has a helmet on already.

In MP this is can only be used for the bike/quad helmets bought in a shop.

