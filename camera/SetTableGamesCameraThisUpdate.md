---
ns: CAMERA
aliases: ["0x79c0e43eb9b944e2"]
---
## SET_TABLE_GAMES_CAMERA_THIS_UPDATE

```c
// 0x79C0E43EB9B944E2
bool SET_TABLE_GAMES_CAMERA_THIS_UPDATE(int cameraType);
```

Overrides the third person camera to be a Table Games Camera on this update only. Returns TRUE if successful.

## cameraType Values:
| Value | Name |
| --- | --- |
| 80 | Black Jack |
| 81 | Lucky Wheel |
| 82 | Slot Machine |
| 83 | Roulette |
| 84 | Poker |
| 85 | Inside Track |
| 86 | Love Professor P1 |
| 87 | Love Professor P2 |


## Parameters
* **cameraType**: The of the custom table games camera to be used.
