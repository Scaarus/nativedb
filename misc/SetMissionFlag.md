---
ns: MISC
aliases: ["0xc4301e5121a0ed73"]
---
## SET_MISSION_FLAG

```c
// 0xC4301E5121A0ED73
void SET_MISSION_FLAG(bool MissionFlagValue);
```

Sets the script as a mission script.

FlagOnAMission should be a BOOL. Every time the player starts a mission, you must remember to set this variable to TRUE. If the flag is TRUE, it will be set back to FALSE when you call MISSION_HAS_FINISHED. Use this instead of DECLARE_MISSION_FLAG

