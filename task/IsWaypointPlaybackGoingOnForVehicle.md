---
ns: TASK
aliases: ["0xf5134943ea29868c"]
---
## IS_WAYPOINT_PLAYBACK_GOING_ON_FOR_VEHICLE

```c
// 0xF5134943EA29868C
bool IS_WAYPOINT_PLAYBACK_GOING_ON_FOR_VEHICLE(Vehicle vehicle);
```

Returns whether the given vehicle is running a script-given waypoint-recording task. This returns true regardless of whether the recording is paused, or an event has taken precedence. You should always use [GET_SCRIPT_TASK_STATUS](#_0x77F1BEB8863288D5) if you need to differentiate between activedormant tasks.

