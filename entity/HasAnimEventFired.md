---
ns: ENTITY
aliases: ["0xeaf4cd9ea3e7e922"]
---
## HAS_ANIM_EVENT_FIRED

```c
// 0xEAF4CD9EA3E7E922
bool HAS_ANIM_EVENT_FIRED(int EventHash);
```

Searches the entity for an animation event. more info...

Use this to check if a particyular event tag is present in an animation playing on the entity this frame Some events are instantaneous (so this will only return true once). Others may have duration, which means that this function may continuously return true for a range of values. The event must have been tagged with the VisibleToScript attribute to make it detectable with this command. Events can include one or more attributes of different types that can be used to get data from the animation. To get the value of an attribute, use the GET_X_ATTRIBUTE_FROM_ANIM_EVENT commands below.


## Parameters
* **EventHash**: The hash of the event name to search for.
