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

## eIcon Values:
| Value | Name |
| --- | --- |
| 0 | Blank |
| 1242 | Message |
| 1243 | Email |
| 1244 | New Contact |
| 1245 | Driver |
| 1246 | Hacker |
| 1247 | Shooter |
| 1248 | Invite |
| 1249 | Rp |
| 1250 | Cash |
| 1251 | Ap |
| 1252 | Xp Alt |
| 1253 | Cash Alt |


## Parameters
* **sTXD**: The Texture Dictionary for the contact image used in the Text Message
* **sImageName**: The Image name string for the contact image used in the Text Message
* **IsImportant**: T
* **eIcon**: Icon type.
* **sCharacterName**: The Character's Name.
* **sSubtitle**: Text label of subtitle
