---
ns: HUD
aliases: ["0x15803fec3b9a872b"]
---
## SET_WARNING_MESSAGE_WITH_HEADER_AND_SUBSTRING_FLAGS_EXTENDED

```c
// 0x15803FEC3B9A872B
void SET_WARNING_MESSAGE_WITH_HEADER_AND_SUBSTRING_FLAGS_EXTENDED(string pHeaderTextLabel, string pBodyTextLabel, Any* iButtonFlagBitfieldLower, Any* iButtonFlagBitfieldUpper, string pBodySubTextLabel, bool InsertNumber, int NumberToInsert, int SubStringFlags, string pFirstSubStringTextLabel, string pSecondSubStringTextLabel, bool Background, int errorNumber);
```

sets a warning message with buttons. Must be called every frame

## SubStringFlags Values:
| Value | Name |
| --- | --- |
| 0 | Default |
| 1 | First Substring Is Literal |
| 2 | Second Substring Is Literal |


iButtonFlagBitfield should be made up of the constants that begin with FE_WARNING_ (declared in frontend_enums.sch / frontend.xml). You can combine several of these using the | operator SubStringFlags allows one or both of the substrings to be literal strings so that the names of UGC missions can be displayed.

