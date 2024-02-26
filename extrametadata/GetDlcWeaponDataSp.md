---
ns: EXTRAMETADATA
aliases: ["0x310836ee7129ba33"]
---
## GET_DLC_WEAPON_DATA_SP

```c
// 0x310836EE7129BA33
bool GET_DLC_WEAPON_DATA_SP(int dlcIndex, Any* weapon);
```

Looks up a sp weapon based on the supplied dlc index (dlcIndex must be inside range: (0 <= dlcIndex < [GET_NUM_DLC_WEAPONS](#_0xEE47635F352DA367)()) )

