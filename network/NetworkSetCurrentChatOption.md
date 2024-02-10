---
ns: NETWORK
aliases: ["0x179b6b0569a08f3c"]
---
## NETWORK_SET_CURRENT_CHAT_OPTION

```c
// 0x179B6B0569A08F3C
void NETWORK_SET_CURRENT_CHAT_OPTION(int newChatOption);
```

Saves a value for the selected chat option for use in metrics sent from code that wish to use that information


## Parameters
* **newChatOption**: Which chat option is currently set in the menu, parameter is CHAT_{OPTION} const ints
