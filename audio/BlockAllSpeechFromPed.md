---
ns: AUDIO
aliases: ["0xf8ad2eed7c47e8fe"]
---
## BLOCK_ALL_SPEECH_FROM_PED

```c
// 0xF8AD2EED7C47E8FE
void BLOCK_ALL_SPEECH_FROM_PED(Ped ped, bool ShouldBlock, bool SuppressOutgoingNetworkSpeech);
```

```
Blocks *all* speech playing on the given ped, including speech triggered by script commands such as PLAY_PED_AMBIENT_SPEECH_WITH_VOICE_NATIVE The flag itself is not synced, it must be called on each machine that wishes to suppress the speech. The SuppressOutgoingNetworkSpeech flag can be set to false if you want speech triggered locally through PLAY_AMBIENT_SPEECH calls to still be audible on remote machines, even though it was blocked on the local one.
```
