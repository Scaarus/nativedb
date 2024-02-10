---
ns: AUDIO
aliases: ["0xa3b0c41ba5cc0bb5"]
---
## STOP_SOUND

```c
// 0xA3B0C41BA5CC0BB5
void STOP_SOUND(int SoundId);
```

```
Stops a playing sound by its sound id.

SoundId must be specified when triggering the sound effect and must be referred to when calling STOP_SOUND. Calling STOP_SOUND on a sound that has finished playing will have no ill effects as long as the SoundId hasn't been released; attempting to stop an invalid SoundId will cause an assert.
```
