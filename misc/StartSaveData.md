---
ns: MISC
aliases: ["0xa9575f812c6a7997"]
---
## START_SAVE_DATA

```c
// 0xA9575F812C6A7997
void START_SAVE_DATA(int SizeOfStruct, bool SinglePlayer);
```

Starts a new block of data. You must call this before calling any of the REGISTER_ commands You must call STOP_SAVE_DATA after REGISTERing the saved variables and the start, registering and stop have to be done in a single frame.
