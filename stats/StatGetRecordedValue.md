---
ns: STATS
aliases: ["0xf11f01d98113536a"]
---
## STAT_GET_RECORDED_VALUE

```c
// 0xF11F01D98113536A
bool STAT_GET_RECORDED_VALUE(float value);
```

PURPOSE Get the recorded stat value NOTES This can be called at anytime. Will retrieve the last recorded value after a stop, or the current value while recording. If no value has been recorded, returns false and the value is unchanged.

