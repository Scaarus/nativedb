---
ns: STREAMING
aliases: ["0xaab3200ed59016bc"]
---
## SWITCH_TO_MULTI_FIRSTPART

```c
// 0xAAB3200ED59016BC
void SWITCH_TO_MULTI_FIRSTPART(Ped ped, int flags, int type);
```

```
Possible values for flags:
| Index | Name |
| --- | --- |
| 1 | Skip Intro |
| 2 | Skip Outro |
| 4 | Pause Before Pan |
| 8 | Pause Before Outro |
| 16 | Skip Pan |
| 32 | Unknown Dest |
| 64 | Descent Only |
| 128 | Start From Campos |
| 256 | Pause Before Ascent |
| 512 | Pause Before Descent |
| 1024 | Allow Sniper Aim Intro |
| 2048 | Allow Sniper Aim Outro |
| 4096 | Skip Top Descent |
| 8192 | Suppress Outro Fx |
| 16384 | Suppress Intro Fx |
| 32768 | Delay Ascent Fx |


Possible values for type:
| Index | Name |
| --- | --- |
| 0 | Auto |
| 18 | Long |
| 19 | Medium |
| 20 | Short |


only use LONG switch here unless you've already checked the distance using GET_IDEAL_SWITCH_TYPE

starts the ascent and hold part of the player switch (when going from SP to MP)
```
