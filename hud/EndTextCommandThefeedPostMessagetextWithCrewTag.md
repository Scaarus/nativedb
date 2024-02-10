---
ns: HUD
aliases: ["0x5cbf7bade20db93e"]
---
## END_TEXT_COMMAND_THEFEED_POST_MESSAGETEXT_WITH_CREW_TAG

```c
// 0x5CBF7BADE20DB93E
int END_TEXT_COMMAND_THEFEED_POST_MESSAGETEXT_WITH_CREW_TAG(string sTXD, string sImageName, bool IsImportant, int eIcon, string sCharacterName, string sSubtitle, float timeMultiplier, string sCrewTagPacked);
```

** Modified TITLE_UPDATE COMMAND ** Displays the text message contact image and localised text message string in the top left of the HUD

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
* **sSubtitle**: Optional Subtitle to display below title
* **timeMultiplier**: Multiplicative modifier to the standard display time of a feed item (2.0f will double the amount of time this feed item is shown on screen)
* **sCrewTagPacked**: Packed crew tag string to show for game invites from crew members
