---
ns: AUDIO
aliases: ["0xfe02ffbed8ca9d99"]
---
## REQUEST_AMBIENT_AUDIO_BANK

```c
// 0xFE02FFBED8CA9D99
bool REQUEST_AMBIENT_AUDIO_BANK(string BankName, bool OverNetwork, int playerBits);
```

Requests and checks that a ambient audio bank has loaded.

This is a legacy function: please use [`REQUEST_SCRIPT_AUDIO_BANK`](#_0x2F844A8B08D76685) instead


## Parameters
* **BankName**: 
* **OverNetwork**: (Default value: `False`)
* **playerBits**: (Default value: `Aud_Net_All_Players`)
