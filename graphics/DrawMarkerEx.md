---
ns: GRAPHICS
aliases: ["0xe82728f0de75d13a"]
---
## DRAW_MARKER_EX

```c
// 0xE82728F0DE75D13A
void DRAW_MARKER_EX(int MarkerType, Vector3 scrVecPosition, Vector3 scrVecDirection, Vector3 scrVecRotation, Vector3 scrVecScale, int colR, int colG, int colB, int colA, bool ounce, bool faceCam, int RotOrder, bool rotate, string txdName, string texName, bool invert, bool usePreAlphaDepth, bool matchEntityRotOrder);
```

```
Possible values for MarkerType:
| Index | Name |
| --- | --- |
| 0 | Cone |
| 1 | Cylinder |
| 2 | Arrow |
| 3 | Arrow Flat |
| 4 | Flag |
| 5 | Ring Flag |
| 6 | Ring |
| 7 | Plane |
| 8 | Bike Logo 1 |
| 9 | Bike Logo 2 |
| 10 | Num 0 |
| 11 | Num 1 |
| 12 | Num 2 |
| 13 | Num 3 |
| 14 | Num 4 |
| 15 | Num 5 |
| 16 | Num 6 |
| 17 | Num 7 |
| 18 | Num 8 |
| 19 | Num 9 |
| 20 | Chevron 1 |
| 21 | Chevron 2 |
| 22 | Chevron 3 |
| 23 | Ring Flat |
| 24 | Lap |
| 25 | Halo |
| 26 | Halo Point |
| 27 | Halo Rotate |
| 28 | Sphere |
| 29 | Money |
| 30 | Lines |
| 31 | Beast |
| 32 | Question Mark |
| 33 | Transform Plane |
| 34 | Transform Helicopter |
| 35 | Transform Boat |
| 36 | Transform Car |
| 37 | Transform Bike |
| 38 | Transform Push Bike |
| 39 | Transform Truck |
| 40 | Transform Parachute |
| 41 | Transform Thruster |
| 42 | Warp |
| 43 | Boxes |
| 44 | Pit Lane |


Possible values for RotOrder:
| Index | Name |
| --- | --- |
| 0 | Xyz |
| 1 | Xzy |
| 2 | Yxz |
| 3 | Yzx |
| 4 | Zxy |
| 5 | Zyx |
| 6 | Max |
```
