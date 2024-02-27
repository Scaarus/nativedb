---
ns: HUD
aliases: ["0x3f5cc444dcaaa8f2"]
---
## SET_HEALTH_HUD_DISPLAY_VALUES

```c
// 0x3F5CC444DCAAA8F2
void SET_HEALTH_HUD_DISPLAY_VALUES(int iHealth, int iArmour, bool ShowDmg);
```

Sets the hud's health display values directly TURNS OFF REAL-TIME QUERYING. So you'll need to turn this off when you're done by passing in iHealth = -1


## Parameters
* **iHealth**: health value to display (assumes it's got a deadpoint of 100 HP) passing in -1 turns this override off
* **iArmour**: armour to display
* **ShowDmg**: (Default value: `True`)
