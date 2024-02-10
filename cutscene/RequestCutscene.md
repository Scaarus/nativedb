---
ns: CUTSCENE
aliases: ["0x7a86743f475d9e09"]
---
## REQUEST_CUTSCENE

```c
// 0x7A86743F475D9E09
void REQUEST_CUTSCENE(string pCutName, int PlaybackFlags);
```

```
Requests a cutscene: animations, models, audio etc.

Possible values for PlaybackFlags:
| Index | Name |
| --- | --- |
| 1 | Requested From Widget |
| 2 | Requested Directly From Skip |
| 4 | Requested From Z Skip |
| 8 | Requested In Mission |
| 16 | Playback Force Load Audio Event |


Should be used for cutscenes that have no fades e.g. a seamless scene
```
