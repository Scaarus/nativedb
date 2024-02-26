---
ns: PATH
aliases: ["0xd0bc1c6fb18ee154"]
---
## SET_GPS_DISABLED_ZONE_AT_INDEX

```c
// 0xD0BC1C6FB18EE154
void SET_GPS_DISABLED_ZONE_AT_INDEX(Vector3 vMin, Vector3 vMax, int index);
```

Can be used to stop GPS functioning in a certain area, or from revealing the route to a certain area.

Currently only 4 slots are available for use To re-enable the GPS, call the function again with a zero-area zone (eg. <0,0,0> to <0,0,0>). Or call [CLEAR_GPS_DISABLED_ZONE_AT_INDEX](#_0x2801D0012266DF07) with the same index It will also be restored automatically upon script termination. The Z coordinate is

Defines a rectangular zone which the GPS will not pathfind through and inserts it at index provided

