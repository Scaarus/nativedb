---
ns: PATH
aliases: ["0xbf1a602b5ba52fee"]
---
## SET_ROADS_IN_AREA

```c
// 0xBF1A602B5BA52FEE
void SET_ROADS_IN_AREA(Vector3 MinPosition, Vector3 MaxPosition, bool Active, bool Network);
```

```
Sets the road node active state in the given area.

All roads are switched on by default

This means that cars will drive on to these roads and new cars will be generated on them. When a road is switched off, no cars should be created on it and cars that already exist will try to avoid driving on to it. To undo a SWITCH_ROADS_ON or a SWITCH_ROADS_OFF, use SWITCH_ROADS_BACK_TO_ORIGINAL.
```
