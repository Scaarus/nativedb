---
ns: OBJECT
aliases: ["0x163e252de035a133"]
---
## GET_OFFSET_FROM_COORD_AND_HEADING_IN_WORLD_COORDS

```c
// 0x163E252DE035A133
Vector3 GET_OFFSET_FROM_COORD_AND_HEADING_IN_WORLD_COORDS(float fHeading, Vector3 vOffset);
```

Similar to GET_OFFSET_FROM_OBJECT_IN_WORLD_COORDS, returns the world coords of the offset relative to the heading passed in

fHeading should be in degrees, code with automatically convert to rads

