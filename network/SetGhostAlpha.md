---
ns: NETWORK
aliases: ["0x658500ae6d723a7e"]
---
## SET_GHOST_ALPHA

```c
// 0x658500AE6D723A7E
void SET_GHOST_ALPHA(int alphavalue);
```

Sets the alpha used for ghosting. This will be reset when the calling script shuts down. You must call this with a value greater than 0 and less than 256.

