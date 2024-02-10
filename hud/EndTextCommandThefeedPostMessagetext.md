---
ns: HUD
aliases: ["0x1ccd9a37359072cf"]
---
## END_TEXT_COMMAND_THEFEED_POST_MESSAGETEXT

```c
// 0x1CCD9A37359072CF
int END_TEXT_COMMAND_THEFEED_POST_MESSAGETEXT(string sTXD, string sImageName, bool IsImportant, int eIcon, string sCharacterName, string sSubtitle);
```

```
Displays the text message contact image and localised text message string in the top left of the HUD

Possible values for eIcon:
| Index | Name |
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
```

## Parameters
* **sTXD**: The Texture Dictionary for the contact image used in the Text Message
* **sImageName**: The Image name string for the contact image used in the Text Message
* **IsImportant**: T
* **eIcon**: Icon type.
* **sCharacterName**: The Character's Name.
* **sSubtitle**: 
