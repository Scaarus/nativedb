---
ns: STATS
aliases: ["0x38baaa5dd4c9d19f"]
---
## SET_PROFILE_SETTING_CREATOR_DM_DONE

```c
// 0x38BAAA5DD4C9D19F
void SET_PROFILE_SETTING_CREATOR_DM_DONE(int newValue);
```

Call this when the player is publishing a DM in the creator. NOTES: Make sure the profile setting value is set on the real stat when we enter the mp game. And because the player can change console make sure we always use the highest value. Make sure you use the command - GET_PROFILE_SETTING( MP_AWD_CREATOR_DM_DONE ) - to get the current value before setting to set 'current+1'.

