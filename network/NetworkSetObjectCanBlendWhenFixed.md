---
ns: NETWORK
aliases: ["0x0379daf89ba09aa5"]
---
## NETWORK_SET_OBJECT_CAN_BLEND_WHEN_FIXED

```c
// 0x0379DAF89BA09AA5
void NETWORK_SET_OBJECT_CAN_BLEND_WHEN_FIXED(Object object, bool CanBlendWhenFixed);
```

Sets whether this script object can use the network blender on remote machines when it is fixed by network. This is only supported for objects (OBJECT_INDEX) currently. This is a targeted helper native to fix syncing issues with the golf ball in GTAV. Please speak to a network programmer before using this for other purposes.

