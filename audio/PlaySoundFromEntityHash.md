---
ns: AUDIO
aliases: ["0x5b9853296731e88d"]
---
## PLAY_SOUND_FROM_ENTITY_HASH

```c
// 0x5B9853296731E88D
void PLAY_SOUND_FROM_ENTITY_HASH(int SoundId, int SoundNameHash, Entity entity, int SetName, bool OverNetwork, int nNetworkRange);
```

Plays back a sound from an entity's location - specified by an Entity_Index.

The sound's position will track the entity's position as it moves. If the sound doesn't need to be stopped (or have variables passed to it) then a soundId of -1 should be used, otherwise use GET_SOUND_ID to assign the sound a SoundId.

