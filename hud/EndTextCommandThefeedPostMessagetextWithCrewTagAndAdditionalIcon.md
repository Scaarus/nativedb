---
ns: HUD
aliases: ["0x531b84e7da981fb6"]
---
## END_TEXT_COMMAND_THEFEED_POST_MESSAGETEXT_WITH_CREW_TAG_AND_ADDITIONAL_ICON

```c
// 0x531B84E7DA981FB6
int END_TEXT_COMMAND_THEFEED_POST_MESSAGETEXT_WITH_CREW_TAG_AND_ADDITIONAL_ICON(string sTXD, string sImageName, bool IsImportant, int eIcon, string sCharacterName, string sSubtitle, float timeMultiplier, string sCrewTagPacked, int eIcon2, int iHudColor);
```

** Modified TITLE_UPDATE COMMAND ** Does everything [`END_TEXT_COMMAND_THEFEED_POST_MESSAGETEXT_WITH_CREW_TAG`](#_0x5CBF7BADE20DB93E) can do, but with an additional icon!

## Values for `eIcon`:
| Value | Name |
| --- | --- |
| 0 | Blank |
| 1 | Message |
| 2 | Email |
| 3 | New Contact |
| 4 | Driver |
| 5 | Hacker |
| 6 | Shooter |
| 7 | Invite |
| 8 | Rp |
| 9 | Cash |
| 10 | Ap |
| 11 | Xp Alt |
| 12 | Cash Alt |


## Parameters
* **sTXD**: 
* **sImageName**: 
* **IsImportant**: 
* **eIcon**: 
* **sCharacterName**: 
* **sSubtitle**: (Default value: `Null`)
* **timeMultiplier**: (Default value: `1`)
* **sCrewTagPacked**: (Default value: `Null`)
* **eIcon2**: (Default value: `0`)
* **iHudColor**: (Default value: `1`)
