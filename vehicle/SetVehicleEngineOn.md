---
ns: VEHICLE
aliases: ["0x2497c4717c8b881e"]
---
## SET_VEHICLE_ENGINE_ON

```c
// 0x2497C4717C8B881E
void SET_VEHICLE_ENGINE_ON(Vehicle vehicle, bool EngineOnFlag, bool NoDelay, bool OnlyStartWithPlayerInput);
```

Sets the vehicles engine.

bNoDelay only has an effect when EngineOnFlag is TRUE. If bNoDelay is TRUE then the engine will start immediately.

