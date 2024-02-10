---
ns: AUDIO
aliases: ["0x2f844a8b08d76685"]
---
## REQUEST_SCRIPT_AUDIO_BANK

```c
// 0x2F844A8B08D76685
bool REQUEST_SCRIPT_AUDIO_BANK(string BankName, bool OverNetwork, int playerBits);
```

```
Requests and checks that a script audio bank has loaded.

Usually this would be called in a loop which only exits when this returns true.
```
