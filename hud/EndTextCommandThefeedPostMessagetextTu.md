---
ns: HUD
aliases: ["0x1e6611149db3db6b"]
---
## END_TEXT_COMMAND_THEFEED_POST_MESSAGETEXT_TU

```c
// 0x1E6611149DB3DB6B
int END_TEXT_COMMAND_THEFEED_POST_MESSAGETEXT_TU(string sTXD, string sImageName, bool IsImportant, int eIcon, string sCharacterName, string sSubtitle, float timeMultiplier);
```

** Modified TITLE_UPDATE COMMAND ** Displays the text message contact image and localised text message string in the top left of the HUD

## eIcon Values:
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
* **sTXD**: The Texture Dictionary for the contact image used in the Text Message
* **sImageName**: The Image name string for the contact image used in the Text Message
* **IsImportant**: T
* **eIcon**: Icon type.
* **sCharacterName**: The Character's Name.
* **sSubtitle**: Optional Subtitle to display below title
* **timeMultiplier**: Multiplicative modifier to the standard display time of a feed item (2.0f will double the amount of time this feed item is shown on screen)
