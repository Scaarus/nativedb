---
ns: HUD
aliases: ["0xd202b92cbf1d816f"]
---
## END_TEXT_COMMAND_THEFEED_POST_REPLAY

```c
// 0xD202B92CBF1D816F
int END_TEXT_COMMAND_THEFEED_POST_REPLAY(int eReplayType, int iIcon, string sSubtitle);
```

```
Displays a Replay feed component (used when you press DPAD down)

Possible values for eReplayType:
| Index | Name |
| --- | --- |
| 1254 | REPLAY_RECORDING |
| 1255 | REPLAY_BUTTON |
| 1256 | ACTION_REPLAY |
```

## Parameters
* **eReplayType**: only use REPLAY_BUTTON_ICON (for now)
* **iIcon**: 
* **sSubtitle**: optional subtitle (not needed for current mockups)
