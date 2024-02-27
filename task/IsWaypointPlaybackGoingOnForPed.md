---
ns: TASK
aliases: ["0xe03b3f2d3dc59b64"]
---
## IS_WAYPOINT_PLAYBACK_GOING_ON_FOR_PED

```c
// 0xE03B3F2D3DC59B64
bool IS_WAYPOINT_PLAYBACK_GOING_ON_FOR_PED(Ped ped);
```

Returns whether the given ped is running a script-given waypoint-recording task. This returns true regardless of whether the recording is paused, or an event has taken precedence. You should always use [`GET_SCRIPT_TASK_STATUS`](#_0x77F1BEB8863288D5) if you need to differentiate between activedormant tasks.

