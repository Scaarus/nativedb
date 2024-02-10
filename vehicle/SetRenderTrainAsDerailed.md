---
ns: VEHICLE
aliases: ["0x317b11a312df5534"]
---
## SET_RENDER_TRAIN_AS_DERAILED

```c
// 0x317B11A312DF5534
void SET_RENDER_TRAIN_AS_DERAILED(Vehicle vehicle, bool Val);
```

Sets the train to look derailed.

If this value is set to true the carriages will be rendered at a slight random angle. This will make it look like the train has derailed. In every other way the train is a normal train and it can still move. The player can still get on it etc.

