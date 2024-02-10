---
ns: PLAYER
aliases: ["0x5d35ecf3a81a0ee0"]
---
## GET_TIME_SINCE_PLAYER_HIT_VEHICLE

```c
// 0x5D35ECF3A81A0EE0
int GET_TIME_SINCE_PLAYER_HIT_VEHICLE();
```

```
Return (in milliseconds) how long ago the player (in a car) last hit a car.

The player has to be in a car himself to do this. Can be used to detect whether the player is driving recklessly. Before the player hits anything the return value is really large. To see what the command would return use the debug widget: 'Car AI and NodesDisplay Reckless driving debug'
```
