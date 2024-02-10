---
ns: VEHICLE
aliases: ["0x21973bbf8d17edfa"]
---
## SET_TRAIN_TRACK_SPAWN_FREQUENCY

```c
// 0x21973BBF8D17EDFA
void SET_TRAIN_TRACK_SPAWN_FREQUENCY(int iTrackIndex, int iTimeMS);
```

```
Time value is in millisecs; using -1 will set the train track spawn freq back to default (also done automatically at end of mission scripts) You'll need to speak with John to find out which track is which in-game This defines the maximum frequency

Specifies the maximum spawn frequency for trains on the specified track; trains will not be generated more frequently that this.
```
