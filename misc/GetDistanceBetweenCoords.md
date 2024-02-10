---
ns: MISC
aliases: ["0xf1b760881820c952"]
---
## GET_DISTANCE_BETWEEN_COORDS

```c
// 0xF1B760881820C952
float GET_DISTANCE_BETWEEN_COORDS(Vector3 FirstPosition, Vector3 SecondPosition, bool Check3d);
```

Gets the distance between 2 coords.

For 2d checks use only the x and y components of the vector as the z value is zeroed by the code.

