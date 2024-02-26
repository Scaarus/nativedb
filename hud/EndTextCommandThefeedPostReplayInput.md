---
ns: HUD
aliases: ["0xdd6cb2cce7c2735c"]
---
## END_TEXT_COMMAND_THEFEED_POST_REPLAY_INPUT

```c
// 0xDD6CB2CCE7C2735C
int END_TEXT_COMMAND_THEFEED_POST_REPLAY_INPUT(int eReplayType, string sIcon, string sSubtitle);
```

Displays a Replay feed component (used when you press DPAD down)

## eReplayType Values:
| Value | Name |
| --- | --- |
| 0 | REPLAY_RECORDING |
| 1 | REPLAY_BUTTON |
| 2 | ACTION_REPLAY |


## Parameters
* **eReplayType**: only use REPLAY_BUTTON_ICON (for now)
* **sIcon**: 
* **sSubtitle**: optional subtitle (not needed for current mockups)
