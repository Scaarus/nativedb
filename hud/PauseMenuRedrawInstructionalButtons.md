---
ns: HUD
aliases: ["0x4895bdea16e7c080"]
---
## PAUSE_MENU_REDRAW_INSTRUCTIONAL_BUTTONS

```c
// 0x4895BDEA16E7C080
void PAUSE_MENU_REDRAW_INSTRUCTIONAL_BUTTONS(int iUniqueId);
```

Redraws the currently active menus instructional buttons. Useful if you've adjusted contexts

DO NOT SPAM THIS. It'll force a redraw and look ugly and be slow and everyone will laugh at you


## Parameters
* **iUniqueId**: (Mostly for futureproofing) if you need to override which index it thinks is active (Default value: `0`)
