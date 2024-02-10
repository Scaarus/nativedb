---
ns: STATS
aliases: ["0xc67e2da1cbe759e2"]
---
## SET_PROFILE_SETTING_SP_CHOP_MISSION_COMPLETE

```c
// 0xC67E2DA1CBE759E2
void SET_PROFILE_SETTING_SP_CHOP_MISSION_COMPLETE();
```

Call this when the player completes the "Franklin 0 - Chop" mission in Single Player This will be checked in Multiplayer (using GET_PROFILE_SETTING(SP_CHOP_MISSION_COMPLETE) ) to decide whether the player can transform into Chop when they eat the peyote plant in Franklin's yard.

