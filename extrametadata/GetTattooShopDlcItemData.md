---
ns: EXTRAMETADATA
aliases: ["0xff56381874f82086"]
---
## GET_TATTOO_SHOP_DLC_ITEM_DATA

```c
// 0xFF56381874F82086
bool GET_TATTOO_SHOP_DLC_ITEM_DATA(int tattoo_faction, int tattooIndex, Any* out_Values);
```

Get the total number of messages in the inbox available to be processed

This number may change (bigger or smaller) as we refresh our local inbox

## Values for `tattoo_faction`:
| Value | Name |
| --- | --- |
| 0 | Sp Michael |
| 1 | Sp Franklin |
| 2 | Sp Trevor |
| 3 | Mp Fm |

