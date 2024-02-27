---
ns: STREAMING
aliases: ["0xc208b673ce446b61"]
---
## SET_PLAYER_SWITCH_OUTRO

```c
// 0xC208B673CE446B61
void SET_PLAYER_SWITCH_OUTRO(Vector3 vCamPos, Vector3 vCamRot, float fCamFov, float fCamFarClip, int RotOrder);
```

use this immediately after starting a player switch if the first frame of the outro camera (e.g. motion builder cam etc) isn't the same as the ped position. this allows streaming to request that scene (instead of a sphere around the new ped pos).

## RotOrder Values:
| Value | Name |
| --- | --- |
| 0 | Xyz |
| 1 | Xzy |
| 2 | Yxz |
| 3 | Yzx |
| 4 | Zxy |
| 5 | Zyx |


overrides the end scene for the player switch


## Parameters
* **vCamPos**: 
* **vCamRot**: 
* **fCamFov**: 
* **fCamFarClip**: 
* **RotOrder**: (Default value: `Yxz`)
