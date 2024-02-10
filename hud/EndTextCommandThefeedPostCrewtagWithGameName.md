---
ns: HUD
aliases: ["0x137bc35589e34e1e"]
---
## END_TEXT_COMMAND_THEFEED_POST_CREWTAG_WITH_GAME_NAME

```c
// 0x137BC35589E34E1E
int END_TEXT_COMMAND_THEFEED_POST_CREWTAG_WITH_GAME_NAME(bool IsPrivate, bool ShowLogoFlag, string sCrewString, int iCrewRank, bool FounderStatus, bool IsImportant, int crewId, string sGameName, int iCrewColourR, int iCrewColourG, int iCrewColourB);
```

```
Displays the crew tag component

bIsPrivate false = public, true = private bShowLogoFlag false = no R*, true = R* shown sCrewString Four alphanumeric characters. iCrewRank Rank (0 to 6) bFounderStatus If true, replaces rank symbols with founder symbol.
```

## Parameters
* **IsPrivate**: 
* **ShowLogoFlag**: 
* **sCrewString**: 
* **iCrewRank**: 
* **FounderStatus**: 
* **IsImportant**: T
* **crewId**: the ID of the crew the message is for
* **sGameName**: the game name appears above body text in the condensed font to allow long gamernames.
* **iCrewColourR**: 
* **iCrewColourG**: 
* **iCrewColourB**: 
