---
ns: RECORDING
aliases: ["0x66972397e0757e7a"]
---
## RECORD_GREATEST_MOMENT

```c
// 0x66972397E0757E7A
void RECORD_GREATEST_MOMENT(int greatestMoment, int startTime, int duration);
```

## greatestMoment Values:
| Value | Name |
| --- | --- |
| 0 | FIVE_START_CRIMINAL |
| 5 | CHAIN_REACTION |
| 6 | BIRD_DOWN |
| 7 | SCOPED |
| 8 | TOP_GUN |
| 9 | AIRTIME |
| 10 | UNTOUCHABLE |
| 11 | WHEELIE_RIDER |
| 12 | BUCKLE_UP |
| 13 | ROLLED_OVER |
| 14 | DIZZYING_LAWS |
| 15 | YANK_THE_CORD |
| 16 | ANIMAUL |
| 17 | FULLY_MODDED |
| 18 | GLORY_HOLE |


Record a greatest moment


## Parameters
* **greatestMoment**: the greatest moment to record.
* **startTime**: the start time (from now) to start recording, in milliseconds. This can be in the past. e.g. -5000 means 5 seconds ago.
* **duration**: the duration of the clip to record.
