---
ns: AUDIO
aliases: ["0x8d8686b622b88120"]
---
## PLAY_SOUND_FROM_COORD

```c
// 0x8D8686B622B88120
void PLAY_SOUND_FROM_COORD(int SoundId, string SoundName, Vector3 position, string SetName, bool OverNetwork, int nNetworkRange, bool isExteriorLoc);
```

Plays back a sound from an absolute position. Optionally can specify a sound set which contains the sound.

If isExteriorLoc is set to TRUE, then it will use a portal occlusion environmentGroup. Only use this if the sound is playing outside and needs occlusion.

