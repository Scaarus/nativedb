---
ns: STREAMING
aliases: ["0xa74a541c6884e7b8"]
---
## SET_SRL_TIME

```c
// 0xA74A541C6884E7B8
void SET_SRL_TIME(float time);
```

This function should be called ideally once a frame during playback of a script-driven cutscene that has an SRL. It provides the streaming request list guidance of where in the cutscene we currently are - the parameter should be 0.0 when the cutscene first starts, and then be the number of MILLIseconds since the beginning of the cutscene, i.e. the number of seconds times 1000. Note that this shouldn't necessarily be the number of milliseconds in real time - just the number of milliseconds you would expect if the cutscene were to play back fluently at full framerate. The key is that this needs to be identical in each run, meaning if there is a camera cut at 4000.0, it needs to always happen at 4000.0.

