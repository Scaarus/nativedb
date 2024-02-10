---
ns: PED
aliases: ["0x5f5d1665e352a839"]
---
## ADD_PED_DECORATION_FROM_HASHES

```c
// 0x5F5D1665E352A839
void ADD_PED_DECORATION_FROM_HASHES(Ped ped, int CollectionNameHash, int PresetNameHash);
```

Applies a decoration (tattoos, patches, etc.) to the specified ped.

Same as ADD_PED_DECORATION, but with hashes


## Parameters
* **ped**: 
* **CollectionNameHash**: the hash of the name of the collection where the preset to apply is stored
* **PresetNameHash**: the hash of the name of the preset to apply
