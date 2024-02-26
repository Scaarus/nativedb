---
ns: EXTRAMETADATA
aliases: ["0x6cebe002e58dee97"]
---
## GET_SHOP_PED_QUERY_PROP_INDEX

```c
// 0x6CEBE002E58DEE97
int GET_SHOP_PED_QUERY_PROP_INDEX(int nameHash);
```

Used after calling [SETUP_SHOP_PED_APPAREL_QUERY_TU](#_0x9BDF59818B1E38C1), gets the index within the query results list of the prop with nameHash The returned index can then be passed to [GET_SHOP_PED_QUERY_PROP](#_0xDE44A00999B2837D)

