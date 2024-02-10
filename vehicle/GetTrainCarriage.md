---
ns: VEHICLE
aliases: ["0x08aafd0814722bc3"]
---
## GET_TRAIN_CARRIAGE

```c
// 0x08AAFD0814722BC3
Vehicle GET_TRAIN_CARRIAGE(Vehicle vehicle, int CarriageNumber);
```

he specified carriage of the train with the given engine.

A CarriageNumber of 0 will return a pointer to the engine

ReturnTrainCarriageID will be NULL if the carriage couldn't be found.

