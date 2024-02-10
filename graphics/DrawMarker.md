---
ns: GRAPHICS
aliases: ["0x28477ec23d892089"]
---
## DRAW_MARKER

```c
// 0x28477EC23D892089
void DRAW_MARKER(int MarkerType, Vector3 scrVecPosition, Vector3 scrVecDirection, Vector3 scrVecRotation, Vector3 scrVecScale, int colR, int colG, int colB, int colA, bool ounce, bool faceCam, int RotOrder, bool rotate, string txdName, string texName, bool invert);
```

Draws a marker this frame

## MarkerType Values:
| Value | Name |
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


## Parameters
* **MarkerType**: the type of marker to the drawn
* **scrVecPosition**: position of the marker
* **scrVecDirection**: the direction the marker should face
* **scrVecRotation**: the rotation applied to the marker (in degrees for each axis)
* **scrVecScale**: the scale of the marker in each of the 3 dimensions
* **colR**: 
* **colG**: 
* **colB**: 
* **colA**: 
* **ounce**: whether the marker should bounce up and down
* **faceCam**: whether the marker should face the camera
* **RotOrder**: 
* **rotate**: whether the marker should rotate automatically on the Z axis.
* **txdName**: streamed texture dictionary name
* **texName**: streamed texture name
* **invert**: render inverted
