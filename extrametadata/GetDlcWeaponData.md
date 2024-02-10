---
ns: EXTRAMETADATA
aliases: ["0x79923cd21bece14e"]
---
## GET_DLC_WEAPON_DATA

```c
// 0x79923CD21BECE14E
bool GET_DLC_WEAPON_DATA(int dlcIndex, scrshopweapondata weapon);
```

Looks up a weapon based on the supplied dlc index (dlcIndex must be inside range: (0 <= dlcIndex < GET_NUM_DLC_WEAPONS()) )

