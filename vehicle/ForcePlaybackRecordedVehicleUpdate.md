---
ns: VEHICLE
aliases: ["0x1f2e4e06dea8992b"]
---
## FORCE_PLAYBACK_RECORDED_VEHICLE_UPDATE

```c
// 0x1F2E4E06DEA8992B
void FORCE_PLAYBACK_RECORDED_VEHICLE_UPDATE(Vehicle vehicle, bool DoPlaceOnRoadAdjustment);
```

```
Forces through a playback update of a vehicle recording, allowing this to be performed on the same game update that the request is made to start playback. This makes it easier to synchronise vehicle recordings with entity warping and scripted camera cuts.
```
