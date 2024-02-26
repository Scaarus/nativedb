---
ns: HUD
aliases: ["0x71a78003c8e71424"]
---
## REQUEST_ADDITIONAL_TEXT

```c
// 0x71A78003C8E71424
void REQUEST_ADDITIONAL_TEXT(string pTextBlockName, int SlotNumber);
```

Requests a block of text.

## SlotNumber Values:
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


One block of text can be loaded into each slot at a time, e.g. the phone script can load a block of text into the phone text slot without affecting the text loaded into the mission text slot for the current mission. In the text file, it is possible to mark a piece of text so that it is only loaded when this command is called. The block is given a name of up to seven characters ? the convention is if the .sc filename has seven or less characters then that name is used in the text file, if the .sc filename has more than seven characters then the first six characters and the last one are used. By putting this block name after a : as part of the text key, the text will not be loaded until REQUEST_ADDITIONAL_TEXT is called using the block name. If any block names are used in the text file then they should be added to an alphabetical list at the very beginning of the text file contained within the words "start" and "end". Only one chunk of block text can be loaded into each slot at a time. When REQUEST_ADDITIONAL_TEXT is called for another block, the block text currently in memory will be lost. It seems that REQUEST_ADDITIONAL_TEXT will also clear any prints on screen and clear the print queue, regardless of the text block that these prints are in. If you're wondering why your text is disappearing this might be the cause. For episodic content, REQUEST_ADDITIONAL_TEXT will not let you override text blocks. i.e. if you have named a text block RAY1 in an episodic gxt and there is already a text block called RAY1 in GTA4's gxt then REQUEST_ADDITIONAL_TEXT will always load the one from GTA4. The solution is to rename the text block to something that doesn't clash.

