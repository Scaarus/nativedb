---
ns: HUD
aliases: ["0x2a179df17ccf04cd"]
---
## CLEAR_ADDITIONAL_TEXT

```c
// 0x2A179DF17CCF04CD
void CLEAR_ADDITIONAL_TEXT(int SlotNumber, bool ClearPreviousBriefs);
```

Call this command to remove the text from the previous attempt at the mission from the previous briefs screen.

## Values for `SlotNumber`:
| Value | Name |
| --- | --- |
| 0 | MISSION_TEXT_SLOT |
| 1 | PHONE_TEXT_SLOT |
| 2 | ODDJOB_TEXT_SLOT |
| 3 | MINIGAME_TEXT_SLOT |
| 4 | SHOP_TEXT_SLOT |
| 5 | OBJECT_TEXT_SLOT |
| 6 | MISSION_DIALOGUE_TEXT_SLOT |
| 7 | AMBIENT_DIALOGUE_TEXT_SLOT |
| 8 | MP_STATS_TEXT_SLOT |
| 9 | MENU_TEXT_SLOT |
| 10 | PROPERTY_TEXT_SLOT |
| 11 | DLC_TEXT_SLOT0 |
| 12 | DLC_TEXT_SLOT1 |
| 13 | DLC_TEXT_SLOT2 |
| 14 | DLC_MISSION_DIALOGUE_TEXT_SLOT |
| 15 | DLC_AMBIENT_DIALOGUE_TEXT_SLOT |
| 16 | RADIO_WHEEL_TEXT_SLOT_RESERVED_FOR_CODE_USE |
| 17 | BINK_MOVIE_TEXT_SLOT |
| 18 | BINK_MOVIE_TEXT_SLOT1 |
| 19 | BINK_MOVIE_TEXT_SLOT2 |
| 20 | DLC_MISSION_DIALOGUE_TEXT_SLOT2 |
| 21 | CREDITS_TEXT_SLOT |


You will probably always want to call this command with TRUE for bClearPreviousBriefs. The reason for adding this command was for the situation where the player fails a mission and then replays it.

