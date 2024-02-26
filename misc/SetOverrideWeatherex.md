---
ns: MISC
aliases: ["0x1178e104409fe58c"]
---
## SET_OVERRIDE_WEATHEREX

```c
// 0x1178E104409FE58C
void SET_OVERRIDE_WEATHEREX(string Weather, bool resetWetness);
```

Sets a weather override for network games. This will fix the weather until [CLEAR_OVERRIDE_WEATHER](#_0x338D2E3477711050) is called. ResetWetness=TRUE resets wetness immediately.

