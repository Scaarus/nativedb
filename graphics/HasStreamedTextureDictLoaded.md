---
ns: GRAPHICS
aliases: ["0x0145f696aaaad2e4"]
---
## HAS_STREAMED_TEXTURE_DICT_LOADED

```c
// 0x0145F696AAAAD2E4
bool HAS_STREAMED_TEXTURE_DICT_LOADED(string TxdName);
```

```
Checks that the streamed tecture dictionary has loaded.

After requesting a streamed txd, call this command to check when the txd has finished streaming. It will return TRUE once the txd has loaded.
```
