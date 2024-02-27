---
ns: STATS
aliases: ["0x176852acaac173d1"]
---
## PLAYSTATS_SHOP_ITEM

```c
// 0x176852ACAAC173D1
void PLAYSTATS_SHOP_ITEM(int itemHash, int cashSpent, int shopNameHash, int extraItemHash, int colorHash);
```

Metric that gets sent when a piece of clothing is bought.


## Parameters
* **itemHash**: Unique Id of the item of clothing.
* **cashSpent**: Amount which the player paid for the item.
* **shopNameHash**: Hash of the shop name.
* **extraItemHash**: additional item type for weaponvehicleother hashes. (Default value: `0`)
* **colorHash**: Parameter for the type of colour being applied when purchasing vehicle colours (i.e. classicmetallicmatte). (Default value: `0`)
