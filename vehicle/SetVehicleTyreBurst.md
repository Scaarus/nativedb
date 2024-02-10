---
ns: VEHICLE
aliases: ["0xec6a202ee4960385"]
---
## SET_VEHICLE_TYRE_BURST

```c
// 0xEC6A202EE4960385
void SET_VEHICLE_TYRE_BURST(Vehicle vehicle, int WheelNumber, bool InstantBurst, float Damage);
```

Sets a vehicles tyre burst.

## WheelNumber Values:
| Value | Name |
| --- | --- |
| 0 | Car Front Left |
| 52 | Car Front Right |
| 53 | Car Mid Left |
| 54 | Car Mid Right |
| 55 | Car Rear Left |
| 56 | Car Rear Right |
| 57 | Bike Front |
| 58 | Bike Rear |


InstantBurst set to true will play burst VFX and tyres will switch to rims

