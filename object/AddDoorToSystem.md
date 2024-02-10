---
ns: OBJECT
aliases: ["0x6f8838d03d1dc226"]
---
## ADD_DOOR_TO_SYSTEM

```c
// 0x6F8838D03D1DC226
void ADD_DOOR_TO_SYSTEM(int doorEnumHash, Hash modelHash, Vector3 vecPos, bool useOldOverrides, bool network, bool permanent);
```

```
Add script defined door to native door system
```

## Parameters
* **doorEnumHash**: 
* **modelHash**: 
* **vecPos**: 
* **useOldOverrides**: 
* **network**: 
* **permanent**: if this is set, the door will not be hooked up with the script and cleaned up when the script terminates. This should only be set to true in special circumstances, it is generally used when entering MP to lock a load of doors permanently during MP. The door system is flushed going back to SP so the doors will be cleaned up then.
