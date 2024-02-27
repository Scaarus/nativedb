---
ns: EXTRAMETADATA
aliases: ["0x31d5e073b6f93cdc"]
---
## GET_DLC_WEAPON_COMPONENT_DATA_SP

```c
// 0x31D5E073B6F93CDC
bool GET_DLC_WEAPON_COMPONENT_DATA_SP(int dlcIndex, int componentIndex, Any* weaponComponent);
```

Looks up a weapon component in SP based on the supplied dlc index and componentIndex NOTE : (dlcIndex must be inside range: (0 <= dlcIndex < [`GET_NUM_DLC_WEAPONS`](#_0xEE47635F352DA367)()) ) NOTE : (componentIndex must be inside range: (0 <= componentIndex < [`GET_NUM_DLC_WEAPON_COMPONENTS`](#_0x405425358A7D61FE)(dlcIndex)) ) NOTE : ModType inside scrShopWeaponComponentData returns a hash of the weapon component's attach point name (and not something sensible, like an enum of component types...)

