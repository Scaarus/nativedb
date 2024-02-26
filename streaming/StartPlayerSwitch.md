---
ns: STREAMING
aliases: ["0xfaa23f2cba159d67"]
---
## START_PLAYER_SWITCH

```c
// 0xFAA23F2CBA159D67
void START_PLAYER_SWITCH(Ped ped, Ped ped, int flags, int type);
```

starts a player switching sequence

## flags Values:
| Value | Name |
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


## type Values:
| Value | Name |
| --- | --- |
| 0 | Auto |
| 1 | Long |
| 2 | Medium |
| 3 | Short |


flags specifies a number of control options as per enum SWITCH_FLAGS

starts player switch

