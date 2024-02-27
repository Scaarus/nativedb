---
ns: HUD
aliases: ["0x5b440763a4c8d15b"]
---
## SET_GPS_FLAGS

```c
// 0x5B440763A4C8D15B
void SET_GPS_FLAGS(int iFlags, float fBlippedRouteDisplayDistance);
```

Sets flags to control GPS behaviour, for routes which use the scripted GPS slot This includes blip-routes, racektrack, and multi-gps routes. Values will be returned to GPS_FLAG_NONE upon mission exit.

## iFlags Values:
| Value | Name |
| --- | --- |
| 0 | None |
| 1 | Ignore One Way |
| 2 | Follow Rules |
| 4 | Avoid Highway |
| 8 | No Route Shift |
| 16 | Custom Proximity |
| 32 | No Pull Path To Right Lane |
| 64 | Avoid Off Road |
| 128 | Ignore Destination Z |


iFlags = bit flags from the GPS_FLAGS enumeration fBlippedRouteDisplayDistance = the distance which a blipped entity must be away from the player before a GPS route to them is displayed; use this to avoid displaying a GPS for entities which are close enough to the player (defaults to zero)


## Parameters
* **iFlags**: 
* **fBlippedRouteDisplayDistance**: (Default value: `0`)
