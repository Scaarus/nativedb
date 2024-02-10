---
ns: AUDIO
aliases: ["0xc6941b4a3a8fbbb9"]
---
## PLAY_PED_AMBIENT_SPEECH_AND_CLONE_NATIVE

```c
// 0xC6941B4A3A8FBBB9
void PLAY_PED_AMBIENT_SPEECH_AND_CLONE_NATIVE(Ped ped, string Context, string Params, bool SyncOverNetwork);
```

Plays a line of a ped's ambient dialogue and clones it across the network.


## Parameters
* **ped**: 
* **Context**: speech context to be spoken
* **Params**: name of the speechParam rave game object to look to for various details on how it should be played
* **SyncOverNetwork**: Indicates whether this speech should automatically by played on clones of the ped on remote machines
