---
ns: PLAYER
aliases: ["0xe36a25322dc35f42"]
---
## GET_TIME_SINCE_PLAYER_HIT_PED

```c
// 0xE36A25322DC35F42
int GET_TIME_SINCE_PLAYER_HIT_PED();
```

```
Returns (in milliseconds) how long ago the player (in a car) last hit a ped.

The player has to be in a car himself to do this. Can be used to detect whether the player is driving recklessly. Before the player hits anything the return value is really large. To see what the command would return use the debug widget: 'Car AI and NodesDisplay Reckless driving debug'
```
