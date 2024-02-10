---
ns: STREAMING
aliases: ["0xb5d7b26b45720e05"]
---
## GET_IDEAL_PLAYER_SWITCH_TYPE

```c
// 0xB5D7B26B45720E05
switch_type GET_IDEAL_PLAYER_SWITCH_TYPE(Vector3 vStartPos, Vector3 vEndPos);
```

```
this follows the same logic as used by the player switch system when auto-selecting switch type

Possible return values:
| Index | Name |
| --- | --- |
| 0 | Auto |
| 18 | Long |
| 19 | Medium |
| 20 | Short |


returns the ideal type of player switch based on the distance from start to end positions.
```
