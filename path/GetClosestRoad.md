---
ns: PATH
aliases: ["0x132f52bba570fe92"]
---
## GET_CLOSEST_ROAD

```c
// 0x132F52BBA570FE92
bool GET_CLOSEST_ROAD(Vector3 TestPosition, float MinLength, int MinLanes, Vector3 SouthEndNode, Vector3 NorthEndNode, int LanesGoingSouth, int LanesGoingNorth, float CentralReservationWidth, bool IgnoreSwitchedOffNodes);
```

WIill return if can the closest road segment of a certein length with a certain number of lanes.


## Parameters
* **TestPosition**: Coordinates near which the search for the road segment is executed.
* **MinLength**: Minimum length that the road segment must have to be considered.
* **MinLanes**: Minimum number of lanes (Both directions added together) the road segment must have to be considered. SouthEndNode,
* **SouthEndNode**: 
* **NorthEndNode**: Coordinates of the 2 nodes that define the road segment. (For horizontal roads the command returns the West node in SouthEndNode and the East node in NorthEndNode. LanesGoingSouth,
* **LanesGoingSouth**: 
* **LanesGoingNorth**: Number of lanes that go either way.
* **CentralReservationWidth**: Width of the bit between the 2 directions (in meters) The coordinates being passed back for both nodes are in the middle of the central reservation of there is one. (If not they are on the transition from the lanes going North and the ones going South)
* **IgnoreSwitchedOffNodes**: (Default value: `True`)
