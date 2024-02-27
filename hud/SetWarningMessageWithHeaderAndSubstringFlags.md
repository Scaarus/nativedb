---
ns: HUD
aliases: ["0x701919482c74b5ab"]
---
## SET_WARNING_MESSAGE_WITH_HEADER_AND_SUBSTRING_FLAGS

```c
// 0x701919482C74B5AB
void SET_WARNING_MESSAGE_WITH_HEADER_AND_SUBSTRING_FLAGS(string pHeaderTextLabel, string pBodyTextLabel, Any* iButtonFlagBitfield, string pBodySubTextLabel, bool InsertNumber, int NumberToInsert, int SubStringFlags, string pFirstSubStringTextLabel, string pSecondSubStringTextLabel, bool Background, int errorNumber);
```

sets a warning message with buttons. Must be called every frame

## SubStringFlags Values:
| Value | Name |
| --- | --- |
| 0 | Default |
| 1 | First Substring Is Literal |
| 2 | Second Substring Is Literal |


iButtonFlagBitfield should be made up of the constants that begin with FE_WARNING_ (declared in frontend_enums.sch / frontend.xml). You can combine several of these using the | operator SubStringFlags allows one or both of the substrings to be literal strings so that the names of UGC missions can be displayed.


## Parameters
* **pHeaderTextLabel**: 
* **pBodyTextLabel**: 
* **iButtonFlagBitfield**: 
* **pBodySubTextLabel**: (Default value: `Null`)
* **InsertNumber**: (Default value: `False`)
* **NumberToInsert**: 
* **SubStringFlags**: (Default value: `Default`)
* **pFirstSubStringTextLabel**: (Default value: `Null`)
* **pSecondSubStringTextLabel**: (Default value: `Null`)
* **Background**: (Default value: `True`)
* **errorNumber**: (Default value: `0`)
