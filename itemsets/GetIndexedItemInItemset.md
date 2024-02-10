---
ns: ITEMSETS
aliases: ["0x7a197e2521ee2bab"]
---
## GET_INDEXED_ITEM_IN_ITEMSET

```c
// 0x7A197E2521EE2BAB
Item GET_INDEXED_ITEM_IN_ITEMSET(int indexInSet, Itemset itemset);
```

```
Get an item from the item set, by index.

The first index is 0, the last item in the set has index GET_ITEMSET_SIZE()-1.

Use NATIVE_TO_INT and INT_TO_NATIVE if you need to convert this to an ENTITY_INDEX, PED_INDEX, etc.
```
