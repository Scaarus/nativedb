---
ns: HUD
aliases: ["0xc6f580e4c94926ac"]
---
## END_TEXT_COMMAND_THEFEED_POST_MESSAGETEXT_SUBTITLE_LABEL

```c
// 0xC6F580E4C94926AC
int END_TEXT_COMMAND_THEFEED_POST_MESSAGETEXT_SUBTITLE_LABEL(string sTXD, string sImageName, bool IsImportant, int eIcon, string sCharacterName, string sSubtitle);
```

Displays the text message contact image and localised text message string in the top left of the HUD

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
* **sTXD**: The Texture Dictionary for the contact image used in the Text Message
* **sImageName**: The Image name string for the contact image used in the Text Message
* **IsImportant**: T
* **eIcon**: Icon type.
* **sCharacterName**: The Character's Name.
* **sSubtitle**: Text label of subtitle (Default value: `Null`)
