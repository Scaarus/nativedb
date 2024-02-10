---
ns: HUD
aliases: ["0x202709f4c58a0424"]
---
## BEGIN_TEXT_COMMAND_THEFEED_POST

```c
// 0x202709F4C58A0424
void BEGIN_TEXT_COMMAND_THEFEED_POST(string sMainTextLabel);
```

Begins the text command for "The Feed". End with END_TEXT_COMMAND_THEFEED_POST_STATS, END_TEXT_COMMAND_THEFEED_POST_MESSAGETEXT, etc. Use the standard string creation functionality detailed below before calling the "END_" function. ( eg ADD_TEXT_COMPONENT_FLOAT(...) )


## Parameters
* **sMainTextLabel**: Main text label
