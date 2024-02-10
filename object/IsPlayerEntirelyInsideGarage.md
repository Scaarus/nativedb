---
ns: OBJECT
aliases: ["0x024a60deb0ea69f0"]
---
## IS_PLAYER_ENTIRELY_INSIDE_GARAGE

```c
// 0x024A60DEB0EA69F0
bool IS_PLAYER_ENTIRELY_INSIDE_GARAGE(int GarageHash, Player player, float margin, int boxIndex);
```

```
Returns TRUE if the player is entirely inside the garage. If the player is in a vehicle it uses the vehciles bound volume.
```
