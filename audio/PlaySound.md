---
ns: AUDIO
aliases: ["0x7ff4944cc209192d"]
---
## PLAY_SOUND

```c
// 0x7FF4944CC209192D
void PLAY_SOUND(int SoundId, string SoundName, string SetName, bool OverNetwork, int nNetworkRange, bool enableOnReplay);
```

Plays back a sound with the name SoundName. Optionally can specify a sound set which contains the named sound.

If the sound is to be manipulated - i.e. stopped - then a SoundId should be acquired using [GET_SOUND_ID](#_0x430386FE9BF80B45)(), otherwise use -1. If this is used to play a sound for which no Pan or Speakermask is set by the sound designer, then the sound will play from the map's origin - therefore this should only be used to play frontend sounds like menu bleeps or other artificially panned effects.

