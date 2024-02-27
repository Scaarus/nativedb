---
ns: NETWORK
aliases: ["0xa2f952104fc6dd4b"]
---
## REQUEST_COMMERCE_ITEM_IMAGE

```c
// 0xA2F952104FC6DD4B
bool REQUEST_COMMERCE_ITEM_IMAGE();
```

Returns true if the image is loaded, so it can repeatedly called until the image is available. Once loaded the image is in the TXD:TextureName returned by [`GET_COMMERCE_ITEM_TEXTURENAME`](#_0x722F5D28B61C5EA8) For example, GET_COMMERCE_ITEM_TEXTURENAME returns "TestTexture", the downloaded texture is in TestTexture:TestTexture

