---
ns: STREAMING
aliases: ["0x9baddc94ef83b823"]
---
## BEGIN_SRL

```c
// 0x9BADDC94EF83B823
void BEGIN_SRL();
```

Marks the beginning of a streaming request list. This can be called before playing back a scripted cutscene. If recording is enabled in RAG, the system will record all visible assets and save them to a file once the SRL is done (after the call to [`END_SRL`](#_0x0A41540E63C9EE17)). If recording is disabled (which is normally the case), the recorded assets from the SRL will be requested as the scripted cutscene plays. You must call [`PREFETCH_SRL`](#_0x3D245789CE12982C) before calling this function!

