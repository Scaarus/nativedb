---
ns: AUDIO
aliases: ["0x7345bdd95e62e0f2"]
---
## REQUEST_MISSION_AUDIO_BANK

```c
// 0x7345BDD95E62E0F2
bool REQUEST_MISSION_AUDIO_BANK(string BankName, bool OverNetwork, int playerBits);
```

Requests and checks that a mission audio bank has loaded.

This is a legacy function: please use [`REQUEST_SCRIPT_AUDIO_BANK`](#_0x2F844A8B08D76685) instead


## Parameters
* **BankName**: 
* **OverNetwork**: (Default value: `False`)
* **playerBits**: (Default value: `Aud_Net_All_Players`)
