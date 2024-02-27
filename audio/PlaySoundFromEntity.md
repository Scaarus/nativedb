---
ns: AUDIO
aliases: ["0xe65f427eb70ab1ed"]
---
## PLAY_SOUND_FROM_ENTITY

```c
// 0xE65F427EB70AB1ED
void PLAY_SOUND_FROM_ENTITY(int SoundId, string SoundName, Entity entity, string SetName, bool OverNetwork, int nNetworkRange);
```

Plays back a sound from an entity's location - specified by an Entity_Index.

The sound's position will track the entity's position as it moves. If the sound doesn't need to be stopped (or have variables passed to it) then a soundId of -1 should be used, otherwise use [`GET_SOUND_ID`](#_0x430386FE9BF80B45) to assign the sound a SoundId.


## Parameters
* **SoundId**: 
* **SoundName**: 
* **entity**: 
* **SetName**: (Default value: `Null`)
* **OverNetwork**: (Default value: `False`)
* **nNetworkRange**: (Default value: `0`)
