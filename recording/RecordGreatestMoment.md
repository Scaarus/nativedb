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
| 1 | CHAIN_REACTION |
| 2 | BIRD_DOWN |
| 3 | SCOPED |
| 4 | TOP_GUN |
| 5 | AIRTIME |
| 6 | UNTOUCHABLE |
| 7 | WHEELIE_RIDER |
| 8 | BUCKLE_UP |
| 9 | ROLLED_OVER |
| 10 | DIZZYING_LAWS |
| 11 | YANK_THE_CORD |
| 12 | ANIMAUL |
| 13 | FULLY_MODDED |
| 14 | GLORY_HOLE |


Record a greatest moment


## Parameters
* **greatestMoment**: the greatest moment to record.
* **startTime**: the start time (from now) to start recording, in milliseconds. This can be in the past. e.g. -5000 means 5 seconds ago.
* **duration**: the duration of the clip to record.
