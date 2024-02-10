---
ns: GRAPHICS
aliases: ["0xdfa2ef8e04127dd5"]
---
## REQUEST_STREAMED_TEXTURE_DICT

```c
// 0xDFA2EF8E04127DD5
void REQUEST_STREAMED_TEXTURE_DICT(string TxdName, bool Priority);
```

Requests a texture dictionary to be loaded from an .img file.

The .img file should contain platform-specific txds and the filename should be listed in X:\project\build\common\data\images.txt. After requesting the txd, you should check HAS_STREAMED_TXD_LOADED in the same way as you do for models and animations. This command is a streamed version of LOAD_TXD.

