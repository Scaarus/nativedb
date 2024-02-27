---
ns: OBJECT
aliases: ["0x891804727e0a98b7"]
---
## CREATE_PICKUP_ROTATE

```c
// 0x891804727E0A98B7
Pickup CREATE_PICKUP_ROTATE(Vector3 Position, Vector3 Orientation, int PlacementFlags, int Amount, int RotOrder, Hash modelHash);
```

Creates a pickup spawner which can be referenced by the script and will spawn a pickup whenever the player gets near. This spawner can also regenerate the pickup after it is collected. The spawner is removed when the script terminates.

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
* **Position**: 
* **Orientation**: specifies the pickups orientation in the same way it is done in SET_ENTITY_ROTATION.
* **PlacementFlags**: (Default value: `0`)
* **Amount**: 
* **RotOrder**: (Default value: `Yxz`)
* **modelHash**: (Default value: `0`)
