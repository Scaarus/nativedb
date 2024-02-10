---
ns: AUDIO
aliases: ["0x4e404a9361f75bb2"]
---
## SET_CUSTOM_RADIO_TRACK_LIST

```c
// 0x4E404A9361F75BB2
void SET_CUSTOM_RADIO_TRACK_LIST(string RadioStationName, string TrackListName, bool ForceNow);
```

Queues up a custom track list on the specified radio station. The content in the track list will be played as soon as possible. The station does not have to be frozen.

If ForceNow = TRUE then the current track will be interrupted by the tracklist

