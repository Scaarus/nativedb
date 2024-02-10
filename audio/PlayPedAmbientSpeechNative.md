---
ns: AUDIO
aliases: ["0x8e04fedd28d42462"]
---
## PLAY_PED_AMBIENT_SPEECH_NATIVE

```c
// 0x8E04FEDD28D42462
void PLAY_PED_AMBIENT_SPEECH_NATIVE(Ped ped, string Context, string Params, bool SyncOverNetwork);
```

Plays a line of a ped's ambient dialogue.


## Parameters
* **ped**: 
* **Context**: speech context to be spoken
* **Params**: name of the speechParam rave game object to look to for various details on how it should be played
* **SyncOverNetwork**: Indicates whether this speech should automatically by played on clones of the ped on remote machines
