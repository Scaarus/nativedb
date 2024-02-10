---
ns: EXTRAMETADATA
aliases: ["0x10144267dd22866c"]
---
## GET_TATTOO_SHOP_DLC_ITEM_INDEX

```c
// 0x10144267DD22866C
int GET_TATTOO_SHOP_DLC_ITEM_INDEX(int tattoo_faction, int collectionHash, int presetHash);
```

Returns the index of the tattoo that matches the faction and hash parameters. This index can then be used to call GET_TATTOO_SHOP_DLC_ITEM_DATA

## tattoo_faction Values:
| Value | Name |
| --- | --- |
| 0 | Sp Michael |
| 17 | Sp Franklin |
| 18 | Sp Trevor |
| 19 | Mp Fm |


ify a collectionHash of -1 to check all collections

