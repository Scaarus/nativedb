---
ns: AUDIO
aliases: ["0xd57aaae0e2214d11"]
---
## FREEZE_MICROPHONE

```c
// 0xD57AAAE0E2214D11
void FREEZE_MICROPHONE();
```

allows script to freeze the microphone for a single frame, mantaining its current transform/settings. This command should be called every frame you want to keep the microphone frozen, when you stop calling it it will automatically unfreeze

