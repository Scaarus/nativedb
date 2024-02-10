---
ns: PATH
aliases: ["0x1ee7063b80ffc77c"]
---
## SET_ROADS_BACK_TO_ORIGINAL

```c
// 0x1EE7063B80FFC77C
void SET_ROADS_BACK_TO_ORIGINAL(Vector3 PositionMin, Vector3 PositionMax, bool Network);
```

```
Sets all vehicle nodes back to their original state. (as per the map data).

It is not cool to call a SET_ROADS_IN_AREA(true) to undo a SET_ROADS_IN_AREA(false) because the nodes that were originally off would now be on.
```
