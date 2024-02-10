---
ns: VEHICLE
aliases: ["0x51f30db60626a20e"]
---
## GET_CAN_VEHICLE_BE_PLACED_HERE

```c
// 0x51F30DB60626A20E
bool GET_CAN_VEHICLE_BE_PLACED_HERE(Vector3 VehiclePos, Vector3 eulerAngles, int RotOrder, int LOSFlags);
```

Gets whether the vehicle can be placed at the given location. This uses the low lod chassis bound, if the vehicle doesn't have one it uses the bounding box

## RotOrder Values:
| Value | Name |
| --- | --- |
| 0 | Xyz |
| 1 | Xzy |
| 2 | Yxz |
| 3 | Yzx |
| 4 | Zxy |
| 5 | Zyx |
| 6 | Max |

