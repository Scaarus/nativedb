---
ns: GRAPHICS
aliases: ["0x3bcf567485e1971c"]
---
## SET_TRANSITION_TIMECYCLE_MODIFIER

```c
// 0x3BCF567485E1971C
void SET_TRANSITION_TIMECYCLE_MODIFIER(string ModifierName, float time);
```

time is in SECONDS

Start a transition to a timecycle, either from "nothing" or from the currently active script modifier if there's one. MAKE SURE TO CALL [CLEAR_TIMECYCLE_MODIFIER](#_0x0F07E7745A236711) when you're done. If this doesn't happen the game will from that point on use that filter.

