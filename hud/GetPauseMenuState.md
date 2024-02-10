---
ns: HUD
aliases: ["0x272acd84970869c5"]
---
## GET_PAUSE_MENU_STATE

```c
// 0x272ACD84970869C5
pause_menu_state GET_PAUSE_MENU_STATE();
```

Returns the current state of the pause menu NOTES: Because 'active' is a relatively fluid term depending on your needs, this function expands IS_PAUSE_MENU_ACTIVE (which effectively just checks == PM_READY)

## Return Type Values:
| Value | Name |
| --- | --- |
| 10 | Restarting |
| 15 | Ready |
| 20 | In Store |
| 25 | In Sc Menu |
| 30 | Shutting Down |
| 35 | In Videoeditor |
| 1259 | Inactive Not Initialized At All |
| 1260 | Starting Up In The Process Of Starting Up (Loading Assets, Etc. May Enter This State During A Restart) |

~> Frontend commands

