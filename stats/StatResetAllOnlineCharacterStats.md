---
ns: STATS
aliases: ["0x26d7399b9587fe89"]
---
## STAT_RESET_ALL_ONLINE_CHARACTER_STATS

```c
// 0x26D7399B9587FE89
void STAT_RESET_ALL_ONLINE_CHARACTER_STATS(int prefix);
```

Reset multiplayer stats (start with string "MP") that are prefixed by a certain number (MP0 to MP4) Reset Perfixes are: - MP0_ -> perfix is 0 - MP1_ -> perfix is 1 - MP2_ -> perfix is 2 - MP3_ -> perfix is 3 - MPPLY_ -> perfix is 5 - MPGEN_ -> perfix is 6 - All the other stats have a perfix 7 which is the default perfix value.

