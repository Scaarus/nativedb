---
ns: VEHICLE
aliases: ["0x42a8ec77d5150cbe"]
---
## SET_VEHICLE_STEER_BIAS

```c
// 0x42A8EC77D5150CBE
void SET_VEHICLE_STEER_BIAS(Vehicle vehicle, float Bias);
```

```
Sets a vehicle control bias -1.0f (hard right) to 1.0f (hard left).

The steer bias value gets added to the players control input for that car. The bias is in the range -1.0f (hard right) to 1.0f (hard left). Ie If you set the bias to 0.1 the car will pull to the left a little bit. By modifying the value from frame to frame you can emulate buggered controls or somebody fighting over control of the wheel.
```
