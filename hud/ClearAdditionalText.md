---
ns: HUD
aliases: ["0x2a179df17ccf04cd"]
---
## CLEAR_ADDITIONAL_TEXT

```c
// 0x2A179DF17CCF04CD
void CLEAR_ADDITIONAL_TEXT(int SlotNumber, bool ClearPreviousBriefs);
```

```
Call this command to remove the text from the previous attempt at the mission from the previous briefs screen.

Possible values for SlotNumber:
| Index | Name |
| --- | --- |
| 1002 | MISSION_TEXT_SLOT |
| 1003 | PHONE_TEXT_SLOT |
| 1004 | ODDJOB_TEXT_SLOT |
| 1005 | MINIGAME_TEXT_SLOT |
| 1006 | SHOP_TEXT_SLOT |
| 1007 | OBJECT_TEXT_SLOT |
| 1008 | MISSION_DIALOGUE_TEXT_SLOT |
| 1009 | AMBIENT_DIALOGUE_TEXT_SLOT |
| 1010 | MP_STATS_TEXT_SLOT |
| 1011 | MENU_TEXT_SLOT |
| 1012 | PROPERTY_TEXT_SLOT |
| 1013 | DLC_TEXT_SLOT0 |
| 1014 | DLC_TEXT_SLOT1 |
| 1015 | DLC_TEXT_SLOT2 |
| 1016 | DLC_MISSION_DIALOGUE_TEXT_SLOT |
| 1017 | DLC_AMBIENT_DIALOGUE_TEXT_SLOT |
| 1018 | RADIO_WHEEL_TEXT_SLOT_RESERVED_FOR_CODE_USE |
| 1019 | BINK_MOVIE_TEXT_SLOT |
| 1020 | BINK_MOVIE_TEXT_SLOT1 |
| 1021 | BINK_MOVIE_TEXT_SLOT2 |
| 1022 | DLC_MISSION_DIALOGUE_TEXT_SLOT2 |
| 1023 | CREDITS_TEXT_SLOT |
| 1024 | NUM_ADDITIONAL_TEXT_SLOTS |


You will probably always want to call this command with TRUE for bClearPreviousBriefs. The reason for adding this command was for the situation where the player fails a mission and then replays it.
```
