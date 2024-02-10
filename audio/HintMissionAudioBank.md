---
ns: AUDIO
aliases: ["0x40763ea7b9b783e7"]
---
## HINT_MISSION_AUDIO_BANK

```c
// 0x40763EA7B9B783E7
bool HINT_MISSION_AUDIO_BANK(string BankName, bool OverNetwork, int playerBits);
```

Hints that this bank would be good to load if there are free slots. Does not guarentee loading of the bank - REQUEST_SCRIPT_AUDIO_BANK MUST be used as normal before triggering sounds"

This is a legacy function: please use HINT_SCRIPT_AUDIO_BANK instead

