---
ns: HUD
aliases: ["0x900086f371220b6f"]
---
## SET_GPS_CUSTOM_ROUTE_RENDER

```c
// 0x900086F371220B6F
void SET_GPS_CUSTOM_ROUTE_RENDER(bool On, int iRouteWidthMiniMap, int iRouteWidthPauseMap);
```

Adds a point to a gps cutsom route at the given vector

iRouteWidthMiniMap & iRouteWidthPauseMap define the size of the route on the maps (specifying -1 for either will use the in-game defaults)

Once custom GPS route is defined (by whatever means) this sets it to render, or turns it off

