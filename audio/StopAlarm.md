---
ns: AUDIO
aliases: ["0xa1caddcd98415a41"]
---
## STOP_ALARM

```c
// 0xA1CADDCD98415A41
void STOP_ALARM(string alarmName, bool instantStop);
```

Returns TRUE if a one shot is currently playingprepared

instantStop -> Whether to kill the alarm instantly, or to let the audio system turn it off when it becomes inaudible

