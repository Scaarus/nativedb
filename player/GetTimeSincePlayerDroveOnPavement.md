---
ns: PLAYER
aliases: ["0xd559d2be9e37853b"]
---
## GET_TIME_SINCE_PLAYER_DROVE_ON_PAVEMENT

```c
// 0xD559D2BE9E37853B
int GET_TIME_SINCE_PLAYER_DROVE_ON_PAVEMENT();
```

Returns (in milliseconds) how long ago the player drove on the pavement.

The player has to be in a car himself to do this. Can be used to detect whether the player is driving recklessly. Before the player hits anything the return value is really large. To see what the command would return use the debug widget: 'Car AI and NodesDisplay Reckless driving debug'

