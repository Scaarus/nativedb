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
| 1 | Car Front Right |
| 2 | Car Mid Left |
| 3 | Car Mid Right |
| 4 | Car Rear Left |
| 5 | Car Rear Right |
| 6 | Bike Front |
| 7 | Bike Rear |


InstantBurst set to true will play burst VFX and tyres will switch to rims


## Parameters
* **vehicle**: 
* **WheelNumber**: 
* **InstantBurst**: (Default value: `False`)
* **Damage**: (Default value: `1000`)
