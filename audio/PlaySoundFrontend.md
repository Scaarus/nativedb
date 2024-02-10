---
ns: AUDIO
aliases: ["0x67c540aa08e4a6f5"]
---
## PLAY_SOUND_FRONTEND

```c
// 0x67C540AA08E4A6F5
void PLAY_SOUND_FRONTEND(int SoundId, string SoundName, string SetName, bool enableOnReplay);
```

```
Plays back a sound "frontend" - at full volume, panned centrally. Optionally can specify a sound set which contains the sound.

If the sound is to be manipulated - i.e. it's a looped that needs to be stopped - then a SoundId should be acquired and used, otherwise use -1 for this parameter. If the sound has a Pan or a SpeakerMask set by the sound designer then the it will play using these settings, otherwise it will play from dead ahead (0°).
```
