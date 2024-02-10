---
ns: PATH
aliases: ["0x2eb41072b4c1e4c0"]
---
## GET_STREET_NAME_AT_COORD

```c
// 0x2EB41072B4C1E4C0
void GET_STREET_NAME_AT_COORD(Vector3 searchCoords);
```

Finds the two nearest nodes that have a road name set up for them.

The nearest one returns the string in hashName1. The second one only gets returned if it is within 40 meters of the searchCoords. So hashName2 may be empty(0).

