---
ns: OBJECT
aliases: ["0x03c27e13b42a0e82"]
---
## DOOR_SYSTEM_SET_AUTOMATIC_RATE

```c
// 0x03C27E13B42A0E82
void DOOR_SYSTEM_SET_AUTOMATIC_RATE(int doorEnumHash, float fAutomaticRate, bool network, bool flushState);
```

Set the rate at which the door's open ratio gets adjusted when opening automatically, i.e. the inverse of the time it takes to open.


## Parameters
* **doorEnumHash**: 
* **fAutomaticRate**: 
* **network**: (Default value: `True`)
* **flushState**: (Default value: `False`)
