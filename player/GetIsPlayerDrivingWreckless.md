---
ns: PLAYER
aliases: ["0xf10b44fd479d69f3"]
---
## GET_IS_PLAYER_DRIVING_WRECKLESS

```c
// 0xF10B44FD479D69F3
bool GET_IS_PLAYER_DRIVING_WRECKLESS(Player player, int wreckless);
```

Used to test if the player has performed a WRECKLESS_TYPE. This will be valid over a number of frames depending on the type.

## Values for `wreckless`:
| Value | Name |
| --- | --- |
| 0 | On Pavement |
| 1 | Ran Red Light |
| 2 | Drove Against Traffic |

