---
ns: VEHICLE
aliases: ["0xb3924ecd70e095dc"]
---
## GET_VEHICLE_MOD_VARIATION

```c
// 0xB3924ECD70E095DC
int GET_VEHICLE_MOD_VARIATION(Vehicle vehicle, int modSlot);
```

```
Returns the current mod variation on the given slot, 0 if none active

Possible values for modSlot:
| Index | Name |
| --- | --- |
| 0 | Spoiler |
| 204 | Bumper F |
| 205 | Bumper R |
| 206 | Skirt |
| 207 | Exhaust |
| 208 | Chassis |
| 209 | Grill |
| 210 | Bonnet |
| 211 | Wing L |
| 212 | Wing R |
| 213 | Roof |
| 214 | Engine |
| 215 | Brakes |
| 216 | Gearbox |
| 217 | Horn |
| 218 | Suspension |
| 219 | Armour |
| 220 | Toggle Nitrous |
| 221 | Toggle Turbo |
| 222 | Toggle Subwoofer |
| 223 | Toggle Tyre Smoke |
| 224 | Toggle Hydraulics |
| 225 | Toggle Xenon Lights |
| 226 | Wheels |
| 227 | Rear Wheels |
| 228 | Pltholder |
| 229 | Pltvanity |
| 230 | Interior1 |
| 231 | Interior2 |
| 232 | Interior3 |
| 233 | Interior4 |
| 234 | Interior5 |
| 235 | Seats |
| 236 | Steering |
| 237 | Knob |
| 238 | Plaque |
| 239 | Ice |
| 240 | Trunk |
| 241 | Hydro |
| 242 | Enginebay1 |
| 243 | Enginebay2 |
| 244 | Enginebay3 |
| 245 | Chassis2 |
| 246 | Chassis3 |
| 247 | Chassis4 |
| 248 | Chassis5 |
| 249 | Door L |
| 250 | Door R |
| 251 | Livery |
```

## Parameters
* **vehicle**: vehicle entity index
* **modSlot**: mod slot to query
