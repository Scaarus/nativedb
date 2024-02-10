---
ns: GRAPHICS
aliases: ["0xbf59707b3e5ed531"]
---
## SET_NEXT_PLAYER_TCMODIFIER

```c
// 0xBF59707B3E5ED531
void SET_NEXT_PLAYER_TCMODIFIER(string NextModifierName);
```

```
Set the next modifier to transition too. if a transition was already in progress, the "next modifier" becomes the current one, the delta gets updated properly, and NextModifierName becomes the new next modifier.
```
