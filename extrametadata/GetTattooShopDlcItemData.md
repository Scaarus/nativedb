---
ns: EXTRAMETADATA
aliases: ["0xff56381874f82086"]
---
## GET_TATTOO_SHOP_DLC_ITEM_DATA

```c
// 0xFF56381874F82086
bool GET_TATTOO_SHOP_DLC_ITEM_DATA(int tattoo_faction, int tattooIndex, stattooshopitemvalues out_Values);
```

Get the total number of messages in the inbox available to be processed
This number may change (bigger or smaller) as we refresh our local inbox

## tattoo_faction Values:
| Value | Name |
| --- | --- |
| 0 | Sp Michael |
| 17 | Sp Franklin |
| 18 | Sp Trevor |
| 19 | Mp Fm |

