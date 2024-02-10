---
ns: PATH
aliases: ["0xf3162836c28f9da5"]
---
## GET_POS_ALONG_GPS_TYPE_ROUTE

```c
// 0xF3162836C28F9DA5
bool GET_POS_ALONG_GPS_TYPE_ROUTE(Vector3 ReturnPos, bool StartAtPlayerPos, float fDistanceAlongRoute, int slotType);
```

## slotType Values:
| Value | Name |
| --- | --- |
| 0 | Waypoint |
| 1 | Radar Blip |
| 2 | Discrete |


bStartAtPlayerPos should we project distance from player position or from next node.

Function to get a position along current player GPS route using supplied slot


## Parameters
* **ReturnPos**: 
* **StartAtPlayerPos**: 
* **fDistanceAlongRoute**: distance we want to get position along route.
* **slotType**: type of gps route to check against
