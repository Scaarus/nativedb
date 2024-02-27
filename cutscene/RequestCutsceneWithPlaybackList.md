---
ns: CUTSCENE
aliases: ["0xc23de0e91c30b58c"]
---
## REQUEST_CUTSCENE_WITH_PLAYBACK_LIST

```c
// 0xC23DE0E91C30B58C
void REQUEST_CUTSCENE_WITH_PLAYBACK_LIST(string pCutName, int CutsceneSection, int PlaybackFlags);
```

Requests a cutscene and tells it what sections to play, for branched cutscenes only.

## Values for `CutsceneSection`:
| Value | Name |
| --- | --- |
| 1 | 1 |
| 2 | 2 |
| 4 | 3 |
| 8 | 4 |
| 16 | 5 |
| 32 | 6 |
| 64 | 7 |
| 128 | 8 |
| 256 | 9 |
| 512 | 10 |
| 1024 | 11 |
| 2048 | 12 |
| 4096 | 13 |
| 8192 | 14 |
| 16384 | 15 |
| 32768 | 16 |
| 65536 | 17 |
| 131072 | 18 |
| 262144 | 19 |
| 524288 | 20 |
| 1048576 | 21 |
| 2097152 | 22 |
| 4194304 | 23 |
| 8388608 | 24 |
| 16777216 | 25 |
| 33554432 | 26 |
| 67108864 | 27 |
| 134217728 | 28 |
| 268435456 | 29 |
| 536870912 | 30 |
| 1073741824 | 31 |


## Values for `PlaybackFlags`:
| Value | Name |
| --- | --- |
| 1 | Requested From Widget |
| 2 | Requested Directly From Skip |
| 4 | Requested From Z Skip |
| 8 | Requested In Mission |
| 16 | Playback Force Load Audio Event |


Include the sections you want to play, it will use the first section as the section to start from.


## Parameters
* **pCutName**: 
* **CutsceneSection**: 
* **PlaybackFlags**: (Default value: `Requested In Mission`)
