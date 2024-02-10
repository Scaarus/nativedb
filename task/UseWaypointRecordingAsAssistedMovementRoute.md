---
ns: TASK
aliases: ["0x5a353b8e6b1095b5"]
---
## USE_WAYPOINT_RECORDING_AS_ASSISTED_MOVEMENT_ROUTE

```c
// 0x5A353B8E6B1095B5
void USE_WAYPOINT_RECORDING_AS_ASSISTED_MOVEMENT_ROUTE(string RecordingName, bool UseAsAssistedMovementRoute, float fPathWidth, float fTension);
```

```
Makes the specified recording act as an assisted-movement route for the player The recording can contine to be used for waypoint-following playback as well. Be absolutely sure to turn this back off when no longer required, as it could be costly.
```
