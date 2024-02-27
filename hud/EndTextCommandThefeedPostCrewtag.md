---
ns: HUD
aliases: ["0x97c9e4e7024a8f2c"]
---
## END_TEXT_COMMAND_THEFEED_POST_CREWTAG

```c
// 0x97C9E4E7024A8F2C
int END_TEXT_COMMAND_THEFEED_POST_CREWTAG(bool IsPrivate, bool ShowLogoFlag, string sCrewString, int iCrewRank, bool FounderStatus, bool IsImportant, int crewId, int iCrewColourR, int iCrewColourG, int iCrewColourB);
```

Displays the crew tag component

bIsPrivate false = public, true = private bShowLogoFlag false = no R*, true = R* shown sCrewString Four alphanumeric characters. iCrewRank Rank (0 to 6) bFounderStatus If true, replaces rank symbols with founder symbol.


## Parameters
* **IsPrivate**: 
* **ShowLogoFlag**: 
* **sCrewString**: 
* **iCrewRank**: 
* **FounderStatus**: 
* **IsImportant**: T
* **crewId**: the ID of the crew the message is for
* **iCrewColourR**: (Default value: `0`)
* **iCrewColourG**: (Default value: `0`)
* **iCrewColourB**: (Default value: `0`)
