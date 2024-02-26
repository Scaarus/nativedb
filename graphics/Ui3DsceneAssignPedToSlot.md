---
ns: GRAPHICS
aliases: ["0x98c4fe6ec34154ca"]
---
## UI3DSCENE_ASSIGN_PED_TO_SLOT

```c
// 0x98C4FE6EC34154CA
bool UI3DSCENE_ASSIGN_PED_TO_SLOT(string presetName, Ped ped, int slotIdx, Vector3 posOffset);
```

Assigns a ped to a given slot (slotIdx) for the currently set preset; the preset must have been set previously by calling [UI3DSCENE_PUSH_PRESET](#_0xF1CEA8A4198D8E9A). Call will fail if the preset passed as a parameter does not match the current preset; it will also fail if the ped index is not valid. The posOffset parameter allows to adjust the position of a given ped (e.g.: ped is smaller or taller than the one used for reference when creating the preset).

