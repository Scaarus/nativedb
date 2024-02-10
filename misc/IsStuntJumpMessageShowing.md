---
ns: MISC
aliases: ["0x2272b0a1343129f4"]
---
## IS_STUNT_JUMP_MESSAGE_SHOWING

```c
// 0x2272B0A1343129F4
bool IS_STUNT_JUMP_MESSAGE_SHOWING();
```

Returns true if the stunt jump message is currently being displayed. This will normally start to return true the same frame that IS_STUNT_JUMP_IN_PROGRESS stops returning true (unless the stunt jump was aborted for various reasons).

