---
ns: PATH
aliases: ["0x0027501b9f3b407e"]
---
## SET_ROADS_BACK_TO_ORIGINAL_IN_ANGLED_AREA

```c
// 0x0027501B9F3B407E
void SET_ROADS_BACK_TO_ORIGINAL_IN_ANGLED_AREA(Vector3 vVec1, Vector3 vVec2, float fAreaWidth, bool Network);
```

```
Sets all vehicle nodes back to their original state. (as per the map data). This is to match turning them on in an angled area

It is not cool to call a SET_ROADS_IN_AREA(true) to undo a SET_ROADS_IN_AREA(false) because the nodes that were originally off would now be on.
```
