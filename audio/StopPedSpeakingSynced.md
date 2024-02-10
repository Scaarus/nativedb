---
ns: AUDIO
aliases: ["0xab6781a5f3101470"]
---
## STOP_PED_SPEAKING_SYNCED

```c
// 0xAB6781A5F3101470
void STOP_PED_SPEAKING_SYNCED(Ped ped, bool ShouldDisable);
```

```
Stops a ped from saying any of their ambient dialogue.

This doesn't stop a piece of dialogue that has been triggered. This stops the ability to force ambient dialogue if set to true - however setting it to false, then triggering a context, then setting it to true again will allow this. The ped will also be prevented from speaking on remote machines. Use STOP_PED_SPEAKING if you just want to affect the local machine.
```
