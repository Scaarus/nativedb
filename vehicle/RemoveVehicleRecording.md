---
ns: VEHICLE
aliases: ["0xf1160accf98a3fc8"]
---
## REMOVE_VEHICLE_RECORDING

```c
// 0xF1160ACCF98A3FC8
void REMOVE_VEHICLE_RECORDING(int FileNumber, string pRecordingName);
```

Removes a recording from memory thats not being used.

t can be used to get rid of car recordings that were streamed in but ended up not being used because of skipping a cutscene or the actions of the player.

