---
ns: HUD
aliases: ["0x71a78003c8e71424"]
---
## REQUEST_ADDITIONAL_TEXT

```c
// 0x71A78003C8E71424
void REQUEST_ADDITIONAL_TEXT(string pTextBlockName, int SlotNumber);
```

```
Requests a block of text.

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


One block of text can be loaded into each slot at a time, e.g. the phone script can load a block of text into the phone text slot without affecting the text loaded into the mission text slot for the current mission. In the text file, it is possible to mark a piece of text so that it is only loaded when this command is called. The block is given a name of up to seven characters ? the convention is if the .sc filename has seven or less characters then that name is used in the text file, if the .sc filename has more than seven characters then the first six characters and the last one are used. By putting this block name after a : as part of the text key, the text will not be loaded until REQUEST_ADDITIONAL_TEXT is called using the block name. If any block names are used in the text file then they should be added to an alphabetical list at the very beginning of the text file contained within the words "start" and "end". Only one chunk of block text can be loaded into each slot at a time. When REQUEST_ADDITIONAL_TEXT is called for another block, the block text currently in memory will be lost. It seems that REQUEST_ADDITIONAL_TEXT will also clear any prints on screen and clear the print queue, regardless of the text block that these prints are in. If you're wondering why your text is disappearing this might be the cause. For episodic content, REQUEST_ADDITIONAL_TEXT will not let you override text blocks. i.e. if you have named a text block RAY1 in an episodic gxt and there is already a text block called RAY1 in GTA4's gxt then REQUEST_ADDITIONAL_TEXT will always load the one from GTA4. The solution is to rename the text block to something that doesn't clash.
```
