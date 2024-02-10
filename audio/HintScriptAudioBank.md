---
ns: AUDIO
aliases: ["0xfb380a29641ec31a"]
---
## HINT_SCRIPT_AUDIO_BANK

```c
// 0xFB380A29641EC31A
bool HINT_SCRIPT_AUDIO_BANK(string BankName, bool OverNetwork, int playerBits);
```

```
Hints that this bank would be good to load if there are free slots. Does not guarentee loading of the bank - REQUEST_SCRIPT_AUDIO_BANK MUST be used as normal before triggering sounds"

Just need to be called once!
```
