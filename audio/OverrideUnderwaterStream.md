---
ns: AUDIO
aliases: ["0xf2a9cdabcea04bd6"]
---
## OVERRIDE_UNDERWATER_STREAM

```c
// 0xF2A9CDABCEA04BD6
void OVERRIDE_UNDERWATER_STREAM(string streamName, bool override);
```

```
This command allows a scripter to override the current underwater stream. It needs to be called before going into the water. And it needs to also be called with OVERRIDE_UNDERWATER_STREAM("", false) in order to stop overriding.
```
