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
| 0 | Black Jack |
| 1 | Lucky Wheel |
| 2 | Slot Machine |
| 3 | Roulette |
| 4 | Poker |
| 5 | Inside Track |
| 6 | Love Professor P1 |
| 7 | Love Professor P2 |


## Parameters
* **cameraType**: The of the custom table games camera to be used.
