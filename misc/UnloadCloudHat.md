---
ns: MISC
aliases: ["0xa74802fb8d0b7814"]
---
## UNLOAD_CLOUD_HAT

```c
// 0xA74802FB8D0B7814
void UNLOAD_CLOUD_HAT(string CloudHatName, float TransitionTime);
```

forces a cloud hat to unload, reguardless of the current cloud settings

this is to help with tralers, etc. please don't use this in general


## Parameters
* **CloudHatName**: force a loading of the named cloud hat
* **TransitionTime**: amount of time to fade out the cloudhat, default is 0 seconds.
