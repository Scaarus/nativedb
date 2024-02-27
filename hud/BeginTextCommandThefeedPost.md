---
ns: HUD
aliases: ["0x202709f4c58a0424"]
---
## BEGIN_TEXT_COMMAND_THEFEED_POST

```c
// 0x202709F4C58A0424
void BEGIN_TEXT_COMMAND_THEFEED_POST(string sMainTextLabel);
```

Begins the text command for "The Feed". End with [`END_TEXT_COMMAND_THEFEED_POST_STATS`](#_0x2B7E9A4EAAA93C89), [`END_TEXT_COMMAND_THEFEED_POST_MESSAGETEXT`](#_0x1CCD9A37359072CF), etc. Use the standard string creation functionality detailed below before calling the "END_" function. ( eg [`ADD_TEXT_COMPONENT_FLOAT`](#_0xE7DCB5B874BCD96E)(...) )


## Parameters
* **sMainTextLabel**: Main text label
