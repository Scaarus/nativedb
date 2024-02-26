---
ns: HUD
aliases: ["0x1eac5f91bcbc5073"]
---
## SET_RACE_TRACK_RENDER

```c
// 0x1EAC5F91BCBC5073
void SET_RACE_TRACK_RENDER(bool On);
```

Renders a race track once contsructed.

Once a track has been defined using START_GPS_RACE_TRACK and a sequence of ADD_POINT_TO_GPS_RACE_TRACKs it can be rendered using this command. When done with the race don't forget to call SET_RACE_TRACK_RENDER false (the mission cleanup also does this) or [CLEAR_GPS_RACE_TRACK](#_0x7AA5B4CE533C858B) When the race track is being displayed other trails that belong to blips are not displayed. The one that can be specified by the player in the front end will still work though.

