---
ns: NETWORK
aliases: ["0x722f5d28b61c5ea8"]
---
## GET_COMMERCE_ITEM_TEXTURENAME

```c
// 0x722F5D28B61C5EA8
string GET_COMMERCE_ITEM_TEXTURENAME();
```

Returns null string if image is not available (product has no image path). Otherwise returns the texturetxd name of the items texture Note: Cannot be used to check for texture download state, is just a manipulation of the string returned by GET_COMMERCE_ITEM_IMAGENAME

