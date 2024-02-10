---
ns: MISC
aliases: ["0x74e20c9145fb66fd"]
---
## STOP_SAVE_DATA

```c
// 0x74E20C9145FB66FD
void STOP_SAVE_DATA();
```

Marks the end of a block of data that has been created by START_SAVE_DATA. You must call STOP_SAVE_DATA after REGISTERing the saved variables and the start, registering and stop have to be done in a single frame. When STOP_SAVE_DATA is called, the code will look for any previously-loaded data for this script and write the loaded values into the matching REGISTERed variables

