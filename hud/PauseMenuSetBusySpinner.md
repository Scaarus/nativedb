---
ns: HUD
aliases: ["0xc78e239ac5b2ddb9"]
---
## PAUSE_MENU_SET_BUSY_SPINNER

```c
// 0xC78E239AC5B2DDB9
void PAUSE_MENU_SET_BUSY_SPINNER(int iColumnID, int iSpinnerIndex);
```

Turns onoff the code-driven busy spinner(s) in the pause menu


## Parameters
* **iColumnID**: which column to show on (or rather, which index in data\ui\frontend.xml, PauseMenu\PersistentData\Spinner\Offsets to use) If bVisible is FALSE, this is pretty much ignored (Default value: `No_Spinner`)
* **iSpinnerIndex**: which spinner to use; we can draw up to 3 BUT BE SURE TO TURN IT OFF WHEN YOU'RE DONE (Default value: `0`)
