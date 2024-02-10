---
ns: PLAYER
aliases: ["0xdb89591e290d9182"]
---
## GET_TIME_SINCE_PLAYER_DROVE_AGAINST_TRAFFIC

```c
// 0xDB89591E290D9182
int GET_TIME_SINCE_PLAYER_DROVE_AGAINST_TRAFFIC();
```

```
Returns (in milliseconds) how long ago the player last drove against the flow of traffic.

The player has to be in a car himself to do this. Can be used to detect whether the player is driving recklessly. Before the player hits anything the return value is really large. To see what the command would return use the debug widget: 'Car AI and NodesDisplay Reckless driving debug'
```
