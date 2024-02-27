---
ns: HUD
aliases: ["0xdc38cc1e35b6a5d7"]
---
## SET_WARNING_MESSAGE_WITH_HEADER

```c
// 0xDC38CC1E35B6A5D7
void SET_WARNING_MESSAGE_WITH_HEADER(string pHeaderTextLabel, string pBodyTextLabel, Any* iButtonFlagBitfield, string pBodySubTextLabel, bool InsertNumber, int NumberToInsert, string pFirstSubStringTextLabel, string pSecondSubStringTextLabel, bool Background, int errorNumber);
```

sets a warning message with buttons. No header. Must be called every frame

iButtonFlagBitfield should be made up of the constants that begin with FE_WARNING_ (declared in frontend_enums.sch / frontend.xml). You can combine several of these using the | operator


## Parameters
* **pHeaderTextLabel**: 
* **pBodyTextLabel**: 
* **iButtonFlagBitfield**: 
* **pBodySubTextLabel**: (Default value: `Null`)
* **InsertNumber**: (Default value: `False`)
* **NumberToInsert**: 
* **pFirstSubStringTextLabel**: (Default value: `Null`)
* **pSecondSubStringTextLabel**: (Default value: `Null`)
* **Background**: (Default value: `True`)
* **errorNumber**: (Default value: `0`)
