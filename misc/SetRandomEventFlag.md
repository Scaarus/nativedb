---
ns: MISC
aliases: ["0x971927086cfd2158"]
---
## SET_RANDOM_EVENT_FLAG

```c
// 0x971927086CFD2158
void SET_RANDOM_EVENT_FLAG(bool ThisScriptIsARandomEvent);
```

```
Call this with TRUE when the player chooses to start a random event. This will allow Bugstar to correctly set the bug owner for random event scripts. The flag will automatically be set to FALSE when the script terminates.
```
