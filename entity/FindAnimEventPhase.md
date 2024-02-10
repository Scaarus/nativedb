---
ns: ENTITY
aliases: ["0x07f1be2bccaa27a7"]
---
## FIND_ANIM_EVENT_PHASE

```c
// 0x07F1BE2BCCAA27A7
bool FIND_ANIM_EVENT_PHASE(string pAnimName, string pEventName, float ReturnStartPhase, float ReturnEndPhase);
```

Searches an animation for the start and end phase of an event. more info...

Use this to find an event tag in an animation and get it's start and end phase.


## Parameters
* **pAnimName**: The anim name
* **pEventName**: The event name
* **ReturnStartPhase**: If the event tag is found, it's start phase will be filled in here.
* **ReturnEndPhase**: If the event tag is found, it's end phase will be filled in here. Returns true if the event tag is found, otherwise false.
