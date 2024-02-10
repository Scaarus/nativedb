---
ns: OBJECT
aliases: ["0x1761dc5d8471cbaa"]
---
## IS_PLAYER_PARTIALLY_INSIDE_GARAGE

```c
// 0x1761DC5D8471CBAA
bool IS_PLAYER_PARTIALLY_INSIDE_GARAGE(int GarageHash, Player player, int boxIndex);
```

Returns TRUE if the player is partially inside the garage. If the player is in a vehicle it uses the vehciles bound volume.

