---
ns: AUDIO
aliases: ["0x2cb0075110be1e56"]
---
## SET_RADIO_TRACK_WITH_START_OFFSET

```c
// 0x2CB0075110BE1E56
void SET_RADIO_TRACK_WITH_START_OFFSET(string RadioStationName, string TrackName, int TimeOffsetMs);
```

```
Forces a specific track on a radio station with a given start offset. The station must be frozen, and the track will be queued for immediate playback
```
