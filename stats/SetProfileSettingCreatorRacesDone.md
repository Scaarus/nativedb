---
ns: STATS
aliases: ["0xf1a1803d3476f215"]
---
## SET_PROFILE_SETTING_CREATOR_RACES_DONE

```c
// 0xF1A1803D3476F215
void SET_PROFILE_SETTING_CREATOR_RACES_DONE(int newValue);
```

Call this when the player is publishing a RACE in the creator.

Make sure the profile setting value is set on the real stat when we enter the mp game. And because the player can change console make sure we always use the highest value. Make sure you use the command - GET_PROFILE_SETTING( MP_AWD_CREATOR_RACES_DONE ) - to get the current value before setting to set 'current+1'.

