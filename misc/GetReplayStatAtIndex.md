---
ns: MISC
aliases: ["0x8098c8d6597aae18"]
---
## GET_REPLAY_STAT_AT_INDEX

```c
// 0x8098C8D6597AAE18
int GET_REPLAY_STAT_AT_INDEX(int ArrayIndex);
```

At the start of a new session, you can call this command if the script detects that a mission replay savegame has just loaded and [`HAVE_REPLAY_STATS_BEEN_STORED`](#_0xD642319C54AADEB6)() has returned TRUE. Once you've read all the replay stats, you should trigger an autosave so that the updated stats get saved.

