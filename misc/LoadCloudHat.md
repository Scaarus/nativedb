---
ns: MISC
aliases: ["0xfc4842a34657bfcb"]
---
## LOAD_CLOUD_HAT

```c
// 0xFC4842A34657BFCB
void LOAD_CLOUD_HAT(string CloudHatName, float TransitionTime);
```

forces a cloud hat to load, reguardless of the current cloud settings

this is to help with tralers, etc. please don't use this in general


## Parameters
* **CloudHatName**: force a loading of the named cloud hat
* **TransitionTime**: amount of time to fade in the cloudhat, default is 0 seconds. (Default value: `0`)
