---
ns: OBJECT
aliases: ["0xda05194260cdcdf9"]
---
## CLEAR_GARAGE

```c
// 0xDA05194260CDCDF9
void CLEAR_GARAGE(int garageHash, bool Broadcast);
```

Clear everything within the garage.


## Parameters
* **garageHash**: 
* **Broadcast**: if set an event is sent over the network in MP to clear the garage on all other machines. Please avoid using this if you can.
