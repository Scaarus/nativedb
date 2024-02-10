---
ns: VEHICLE
aliases: ["0xeebfc7a7efdc35b4"]
---
## GET_VEHICLE_COLOURS_WHICH_CAN_BE_SET

```c
// 0xEEBFC7A7EFDC35B4
int GET_VEHICLE_COLOURS_WHICH_CAN_BE_SET(Vehicle vehicle);
```

```
Returns a bitset that shows which colours will have a visible effect when you call one of the "set colour" commands. Use IS_BIT_SET 0,1,2,3,4 for Colours 1,2,3,4,5
```
