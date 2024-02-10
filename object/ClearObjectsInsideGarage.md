---
ns: OBJECT
aliases: ["0x190428512b240692"]
---
## CLEAR_OBJECTS_INSIDE_GARAGE

```c
// 0x190428512B240692
void CLEAR_OBJECTS_INSIDE_GARAGE(int garageHash, bool vehicles, bool peds, bool objects, bool Broadcast);
```

Clear objects within the garage.


## Parameters
* **garageHash**: 
* **vehicles**: 
* **peds**: 
* **objects**: 
* **Broadcast**: if set an event is sent over the network in MP to clear the garage on all other machines. Please avoid using this if you can.
