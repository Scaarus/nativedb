---
ns: NETWORK
aliases: ["0x267c78c60e806b9a"]
---
## NETWORK_ALLOW_REMOTE_ATTACHMENT_MODIFICATION

```c
// 0x267C78C60E806B9A
void NETWORK_ALLOW_REMOTE_ATTACHMENT_MODIFICATION(Entity entity, bool CanModify);
```

Flags an object to allow local attachments for remotely controlled objects - generally this is a bad thing to do but is necessary in some cases (such as remote players using roller coasters, which use local only objects for the carriages


## Parameters
* **entity**: 
* **CanModify**: Indicates whether local modifications are allowed
