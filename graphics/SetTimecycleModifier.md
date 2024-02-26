---
ns: GRAPHICS
aliases: ["0x2c933abf17a1df41"]
---
## SET_TIMECYCLE_MODIFIER

```c
// 0x2C933ABF17A1DF41
void SET_TIMECYCLE_MODIFIER(string ModifierName);
```

Forces the timecycle modifier to be used for 100%.

A timecyclemodifier is set up by an artists and can contains changes to light colour, fog colour, clip plane distance or post fx. They can be used as a filter. Good ones to try are: death, busted, sniper_ini, sniper, binocular, injured, fast MAKE SURE TO CALL [CLEAR_TIMECYCLE_MODIFIER](#_0x0F07E7745A236711) when you're done. If this doesn't happen the game will from that point on use that filter.

