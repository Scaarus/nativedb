---
ns: OBJECT
aliases: ["0x92aefb5f6e294023"]
---
## PREVENT_COLLECTION_OF_PORTABLE_PICKUP

```c
// 0x92AEFB5F6E294023
void PREVENT_COLLECTION_OF_PORTABLE_PICKUP(bool Prevent, bool LocalOnly);
```

Sets a portable pickup to be uncollectable


## Parameters
* **Prevent**: 
* **LocalOnly**: if true then the local player is prohibited from collecting the pickup. This is not synced and is used to prevent collection locally (Default value: `False`)
