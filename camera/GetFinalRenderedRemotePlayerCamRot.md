---
ns: CAMERA
aliases: ["0x26903d9cd1175f2c"]
---
## GET_FINAL_RENDERED_REMOTE_PLAYER_CAM_ROT

```c
// 0x26903D9CD1175F2C
Vector3 GET_FINAL_RENDERED_REMOTE_PLAYER_CAM_ROT(Player player, int RotOrder);
```

Gets the rotation of the final rendered cam for a remote player.

## RotOrder Values:
| Value | Name |
| --- | --- |
| 0 | Xyz |
| 1 | Xzy |
| 2 | Yxz |
| 3 | Yzx |
| 4 | Zxy |
| 5 | Zyx |


## Parameters
* **player**: 
* **RotOrder**: (Default value: `Yxz`)
