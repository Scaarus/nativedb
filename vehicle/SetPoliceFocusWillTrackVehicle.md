---
ns: VEHICLE
aliases: ["0x4e74e62e0a97e901"]
---
## SET_POLICE_FOCUS_WILL_TRACK_VEHICLE

```c
// 0x4E74E62E0A97E901
void SET_POLICE_FOCUS_WILL_TRACK_VEHICLE(Vehicle vehicle, bool NewVal);
```

```
Sets the police focus on the vehicle.

If this is set to true the police focus circle is always focussed on the car. If this is false the player has a chance to escape police attention if undetected. By default law enforcement vehicles have this bit set to true and all other cars have false.
```
