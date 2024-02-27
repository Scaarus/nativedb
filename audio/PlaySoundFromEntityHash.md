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

The sound's position will track the entity's position as it moves. If the sound doesn't need to be stopped (or have variables passed to it) then a soundId of -1 should be used, otherwise use [`GET_SOUND_ID`](#_0x430386FE9BF80B45) to assign the sound a SoundId.


## Parameters
* **SoundId**: 
* **SoundNameHash**: 
* **entity**: 
* **SetName**: (Default value: `0`)
* **OverNetwork**: (Default value: `False`)
* **nNetworkRange**: (Default value: `0`)
