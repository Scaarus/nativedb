---
ns: STATS
aliases: ["0x55384438fc55ad8e"]
---
## SET_PROFILE_SETTING_CREATOR_CTF_DONE

```c
// 0x55384438FC55AD8E
void SET_PROFILE_SETTING_CREATOR_CTF_DONE(int newValue);
```

```
Call this when the player is publishing a CTF in the creator. NOTES: Make sure the profile setting value is set on the real stat when we enter the mp game. And because the player can change console make sure we always use the highest value. Make sure you use the command - GET_PROFILE_SETTING( MP_AWD_CREATOR_CTF_DONE ) - to get the current value before setting to set 'current+1'.
```
