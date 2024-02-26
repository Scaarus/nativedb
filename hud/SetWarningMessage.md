---
ns: HUD
aliases: ["0x7b1776b3b53f8d74"]
---
## SET_WARNING_MESSAGE

```c
// 0x7B1776B3B53F8D74
void SET_WARNING_MESSAGE(string pTextLabel, Any* iButtonFlagBitfield, string pBodySubTextLabel, bool InsertNumber, int NumberToInsert, string pFirstSubStringTextLabel, string pSecondSubStringTextLabel, bool Background, int errorNumber);
```

sets a warning message with buttons. No header. Must be called every frame

iButtonFlagBitfield should be made up of the constants that begin with FE_WARNING_ (declared in frontend_enums.sch / frontend.xml). You can combine several of these using the | operator

