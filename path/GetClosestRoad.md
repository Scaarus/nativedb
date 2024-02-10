---
ns: PATH
aliases: ["0x132f52bba570fe92"]
---
## GET_CLOSEST_ROAD

```c
// 0x132F52BBA570FE92
bool GET_CLOSEST_ROAD(Vector3 TestPosition, float MinLength, int MinLanes, bool IgnoreSwitchedOffNodes);
```

WIill return if can the closest road segment of a certein length with a certain number of lanes.


## Parameters
* **TestPosition**: Coordinates near which the search for the road segment is executed.
* **MinLength**: Minimum length that the road segment must have to be considered.
* **MinLanes**: Minimum number of lanes (Both directions added together) the road segment must have to be considered. SouthEndNode,
* **IgnoreSwitchedOffNodes**: 
