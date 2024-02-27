---
ns: AUDIO
aliases: ["0x8f8c0e370ae62f5c"]
---
## HINT_AMBIENT_AUDIO_BANK

```c
// 0x8F8C0E370AE62F5C
bool HINT_AMBIENT_AUDIO_BANK(string BankName, bool OverNetwork, int playerBits);
```

Hints that this bank would be good to load if there are free slots. Does not guarentee loading of the bank - [`REQUEST_SCRIPT_AUDIO_BANK`](#_0x2F844A8B08D76685) MUST be used as normal before triggering sounds"

This is a legacy function: please use [`HINT_SCRIPT_AUDIO_BANK`](#_0xFB380A29641EC31A) instead


## Parameters
* **BankName**: 
* **OverNetwork**: (Default value: `False`)
* **playerBits**: (Default value: `Aud_Net_All_Players`)
