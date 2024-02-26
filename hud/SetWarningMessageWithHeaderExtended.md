---
ns: HUD
aliases: ["0x38b55259c2e078ed"]
---
## SET_WARNING_MESSAGE_WITH_HEADER_EXTENDED

```c
// 0x38B55259C2E078ED
void SET_WARNING_MESSAGE_WITH_HEADER_EXTENDED(string pHeaderTextLabel, string pBodyTextLabel, Any* iButtonFlagBitfieldLower, Any* iButtonFlagBitfieldUpper, string pBodySubTextLabel, bool InsertNumber, int NumberToInsert, string pFirstSubStringTextLabel, string pSecondSubStringTextLabel, bool Background, int errorNumber);
```

sets a warning message with buttons. No header. Must be called every frame

iButtonFlagBitfield should be made up of the constants that begin with FE_WARNING_ (declared in frontend_enums.sch / frontend.xml). You can combine several of these using the | operator

