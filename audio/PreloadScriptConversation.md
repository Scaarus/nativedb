---
ns: AUDIO
aliases: ["0x3b3cad6166916d87"]
---
## PRELOAD_SCRIPT_CONVERSATION

```c
// 0x3B3CAD6166916D87
void PRELOAD_SCRIPT_CONVERSATION(bool DisplaySubtitles, bool addToBriefScreen, bool cloneConversation, bool Interruptible);
```

```
Similar to START_SCRIPT_CONVERSATION, except that is starts the conversation off paused. A scripter can then kick off the conversation by calling START_PRELOADED_CONVERSATION. If they want to check that the conversation is done preloading, they can use GET_IS_PRELOADED_CONVERSATION_READY
```
