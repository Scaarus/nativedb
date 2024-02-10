---
ns: STREAMING
aliases: ["0x717cd6e6faebbedc"]
---
## SET_GAME_PAUSES_FOR_STREAMING

```c
// 0x717CD6E6FAEBBEDC
void SET_GAME_PAUSES_FOR_STREAMING(bool AllowPause);
```

This should only be called by the end credits script.

The credits will call it with FALSE at the start and TRUE at the end. This is to stop the scrolling of the credits from pausing when the player warps from one area of the city to another during the screen fades.

