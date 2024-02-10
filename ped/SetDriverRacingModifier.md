---
ns: PED
aliases: ["0xded5af5a0ea4b297"]
---
## SET_DRIVER_RACING_MODIFIER

```c
// 0xDED5AF5A0EA4B297
void SET_DRIVER_RACING_MODIFIER(Ped ped, float RacingModifier);
```

RacingModifier must be between 0 and 1 or the value will be rejected 0 = No extra lookahead, try to get back onto the route as quick as possible 1 = No matter how far off the path I am, use the same lookahead as if I were on the path. Increasing RacingModifier can reduce fishtailing in racing missions

Sets a driver's racing modifier--a value between 0 and 1 that adjusts the lookahead when steering along a vehicle path. Ambient vehicles will have a value of 0 for this unless overridden by script.

