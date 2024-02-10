---
ns: AUDIO
aliases: ["0x353fc880830b88fa"]
---
## RELEASE_SOUND_ID

```c
// 0x353FC880830B88FA
void RELEASE_SOUND_ID(int SoundId);
```

Releases a sound ID.

This should be called once a sound has finished being manipulated by the script so that its SoundId can be released and re-used.

