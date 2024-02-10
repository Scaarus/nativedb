---
ns: PATH
aliases: ["0xdc20483cd3dd5201"]
---
## SET_GPS_DISABLED_ZONE

```c
// 0xDC20483CD3DD5201
void SET_GPS_DISABLED_ZONE(Vector3 vMin, Vector3 vMax);
```

```
Can be used to stop GPS functioning in a certain area, or from revealing the route to a certain area.

To re-enable the GPS, call the function again with a zero-area zone (eg. <0,0,0> to <0,0,0>). It will also be restored automatically upon script termination. Can also be restored by calling CLEAR_GPS_DISABLED_ZONE_AT_INDEX(0) The Z coordinate is

Defines a rectangular zone which the GPS will not pathfind through.
```
