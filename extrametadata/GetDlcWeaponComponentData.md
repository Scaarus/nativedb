---
ns: EXTRAMETADATA
aliases: ["0x6cf598a2957c2bf8"]
---
## GET_DLC_WEAPON_COMPONENT_DATA

```c
// 0x6CF598A2957C2BF8
bool GET_DLC_WEAPON_COMPONENT_DATA(int dlcIndex, int componentIndex, Any* weaponComponent);
```

Looks up a weapon component based on the supplied dlc index and componentIndex NOTE : (dlcIndex must be inside range: (0 <= dlcIndex < [GET_NUM_DLC_WEAPONS](#_0xEE47635F352DA367)()) ) NOTE : (componentIndex must be inside range: (0 <= componentIndex < [GET_NUM_DLC_WEAPON_COMPONENTS](#_0x405425358A7D61FE)(dlcIndex)) ) NOTE : ModType inside scrShopWeaponComponentData returns a hash of the weapon component's attach point name (and not something sensible, like an enum of component types...)

