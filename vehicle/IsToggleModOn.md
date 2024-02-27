---
ns: VEHICLE
aliases: ["0x84b233a8c8fc8ae7"]
---
## IS_TOGGLE_MOD_ON

```c
// 0x84B233A8C8FC8AE7
bool IS_TOGGLE_MOD_ON(Vehicle vehicle, int modSlot);
```

Return if the toggle mod on the given slot is turned on or off. More...

## Values for `modSlot`:
| Value | Name |
| --- | --- |
| 0 | Spoiler |
| 1 | Bumper F |
| 2 | Bumper R |
| 3 | Skirt |
| 4 | Exhaust |
| 5 | Chassis |
| 6 | Grill |
| 7 | Bonnet |
| 8 | Wing L |
| 9 | Wing R |
| 10 | Roof |
| 11 | Engine |
| 12 | Brakes |
| 13 | Gearbox |
| 14 | Horn |
| 15 | Suspension |
| 16 | Armour |
| 17 | Toggle Nitrous |
| 18 | Toggle Turbo |
| 19 | Toggle Subwoofer |
| 20 | Toggle Tyre Smoke |
| 21 | Toggle Hydraulics |
| 22 | Toggle Xenon Lights |
| 23 | Wheels |
| 24 | Rear Wheels |
| 25 | Pltholder |
| 26 | Pltvanity |
| 27 | Interior1 |
| 28 | Interior2 |
| 29 | Interior3 |
| 30 | Interior4 |
| 31 | Interior5 |
| 32 | Seats |
| 33 | Steering |
| 34 | Knob |
| 35 | Plaque |
| 36 | Ice |
| 37 | Trunk |
| 38 | Hydro |
| 39 | Enginebay1 |
| 40 | Enginebay2 |
| 41 | Enginebay3 |
| 42 | Chassis2 |
| 43 | Chassis3 |
| 44 | Chassis4 |
| 45 | Chassis5 |
| 46 | Door L |
| 47 | Door R |
| 48 | Livery |


Note that modSlot has to be one of the toggle mods or the function always returns false

