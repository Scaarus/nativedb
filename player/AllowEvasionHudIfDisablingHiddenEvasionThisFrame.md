---
ns: PLAYER
aliases: ["0x2f41a3bae005e5fa"]
---
## ALLOW_EVASION_HUD_IF_DISABLING_HIDDEN_EVASION_THIS_FRAME

```c
// 0x2F41A3BAE005E5FA
void ALLOW_EVASION_HUD_IF_DISABLING_HIDDEN_EVASION_THIS_FRAME(float fTimeBeforeAllowReport);
```

Allow evasion HUD when calling [`SUPPRESS_LOSING_WANTED_LEVEL_IF_HIDDEN_THIS_FRAME`](#_0x4669B3ED80F24B4E)


## Parameters
* **fTimeBeforeAllowReport**: Player will not be reported for this amount of time after command is first called (if set, ie not -1.0). Timer will reset if a different value is passed in if timer is still running. Time is in seconds.
